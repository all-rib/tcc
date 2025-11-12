# Trabalho de Conclusão de Curso - Reloaded [PDF](old-src/main.pdf)

## [Notas gerais de escrita](notes)

## [Source code MELISSA](http://localhost:3000/allanribeiro/melissa)

Sistema embarcado inteiro, inserido na colméia, que une sensores, logs, armazenamento
em massa e transmissão

## [Source code HERMES](http://localhost:3000/allanribeiro/hermes)

Biblioteca de logging, supostamente desnecessariamente robusta, prevendo qualquer problema
no micro.

## [Source code ARISTEU](http://localhost:3000/allanribeiro/aristeu)

Hardware para sensoriamento.

# TODO

- [ ] Talvez separar este TODO entre os respectivos repositórios. Mas não quero ter
que fazer backtracking.
- [ ] Reinstalar ESP-IDF
- [ ] Criar um novo projeto teste e compilar
- [ ] Compilar pelo menos uma versão funcional do teu projeto
	- [ ] Funcionar log
	- [ ] Funcionar bluetooth
	- [ ] Funcionar sensor
- [ ] Reescrever hard fault
- [ ] Unificar tuas branches
- [ ] Unificar tuas bibliotecas
- [ ] Versionar e documentar tudo

## Compilando o source LaTeX

 - Instale o pacote todo texlive no teu linuxão da massa

 - Rode com pdflatex

```
pdflatex -interaction=nonstopmode main.tex
```

## Objetivos

    - Construção do banco de dados
        - Planejamento
          	- Como se constrói uma base de dados? (ambientação)
          	- Quais dados vou extrair? (especificação)
          	  - escolher sensores
          	  - aferir sensores
			Falar com Ana Cris
          	- Como vou extrair estes dados? (metodologia)

        - Extração dos dados
            - Teste em campo dos sensores
            - Construção do hardware
                - Extração "Plug n Play"?
            Falar com Denardin aqui
            - Teste do Hardware
            Falar com Denarin de novo
			Falar com Ana Cris
            - Montagem do hardware
			Falar com Ana Cris de novo

        - Parametrização dos dados
          	Falar com Dalcimar
            - Script para filtragem, se necessária
            - Começar captura
            - Extrair e analisar primeiras amostras
            Falar com Dalcimar de novo
			- Escrever script para automatizar parte anterior
        - Análise dos dados
          	É isso. "Cabo"
          	
# Extração dos dados

Extrair usando STM32
esp32?
	Pros:
		- Já está pronto
		- Economia de energia

	Cons:
		- Pouco armazenamento

Extrair usando raspberry pi
	Quad core 64-bit ARM-Cortex A72, 1.5GHz
	4GB LPDDR4 RAM
	H.265 (HEVC) hardware decode (up to 4Kp60)
	H.264 hardware decode (up to 1080p60
	VideoCore VI 3D Graphics
	Supports dual HDMI display output up to 4Kp60

	- Mais armazenamento
	
	Cons:
		- Gasta uma energia do cão

## Checklist de elementos

- [ ] 00-main.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 01-capa.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 02-contracapa.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 03-termo.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 04-agradecimentos.tex
	- [x] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 05-epigrafe.tex
	- [x] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 06-resumo.tex
	- [x] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 07-abstract.tex
	- [x] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 08-ilustracoes.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 09-tabelas.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 10-acronimos.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 11-sumario.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [x] 12-introducao.tex
	- [x] modelo
	- [x] texto
	- [ ] formatação
- [ ] 13-referencial-teorico.md
	- [ ] modelo
	- [o] texto
	- [ ] formatação
- [ ] 14-materiais-e-metodos.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 15-desenvolvimento.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 16-conclusao.md
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 16-resultados-e-discucao.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação
- [ ] 17-referencias.tex
	- [ ] modelo
	- [ ] texto
	- [ ] formatação


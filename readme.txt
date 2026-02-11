coding:
	- climate_spiral.R || contém o script da ESPIRAL CLIMÁTICA (gráfico animado)
	- data_cleaning || contém o script usado para tratar o dataset INICIAL e salvar o dataset FINAL

dados:
	- climate_dataframe.txt || é o dataframe FINAL utilizado para construer a espiral climática, é esse 	que você deve usar caso queira testar o script .R, Rmd, etc...
	- GLB.Ts+dSST.csv || dataset INICIAL em csv, sem nenhum tratamento e dados ou alteração
	retirado diretamente de (https://data.giss.nasa.gov/gistemp/)

dashboard:
	- dashboard.Rmd || script .Rmd usado para construção do dashboard
	- dashboard.html || arquivo do dashboard final

media:
	- climate_spiral3d.html || protótipo de um gráfico em 3d da espiral climática
	- espiral_clima.gif || gif da animação
	- espiral_clima.mp4 || video da animação (apenas alterado para .mp4)
	- ultimo_frame.png || último frame da animação

relatorio:
	- Relatorio_tecnico.Rmd || script .Rmd do relatório técnico
	- Relatorio_tecnico.html || arquivo final do relatório técnico


recomendo não alterar os nomes das pastas ou arquivos, e nem mudá-los de lugar. para apenas abrir os códigos e rodar, você só precisa definir onde vai salvar as pastas e alterar "...caminho/" nos scripts .R para o tratamento e dados e criação da animação, ou .Rmd para o relatório técnico
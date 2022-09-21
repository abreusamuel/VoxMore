# VoxMore
Plugin criado com o intuito educacional para utilização de professores e alunos de análise acústica vocal
#
Autores: Samuel Abreu, Ronei Moraes e Leonardo Lopes

Contato: abreu.s.ribeiro@gmail.com
#
Este programa é um software livre: você pode redistribuí-lo e/ou modificá-lo sob os termos da Licença Pública Geral GNU, conforme publicado pela Free Software Foundation, seja a versão 3 da Licença ou (a seu critério) qualquer versão posterior.

Este programa é distribuído na esperança de que seja útil, mas SEM QUALQUER GARANTIA; sem a garantia implícita de COMERCIALIZAÇÃO OU ADEQUAÇÃO A UM DETERMINADO PROPÓSITO. Veja a Licença Pública Geral GNU para obter mais detalhes. Você deve ter recebido uma cópia da Licença Pública Geral GNU junto com este programa. Veja <https://www.gnu.org/licenses/>.

Esse plugin foi testado na versão 6.2.10 do Praat.
#
Plugin feito para análise acústica de vogal sustentada amostrada em 44.100 Hz e gravação mono. As amostras de voz que foram testadas pelos autores segue a gravação conforme o seguinte artigo: Lopes LW, Sousa ESDS, Silva ACFD, Silva IMD, Paiva MAAD, Vieira VJD, Almeida AA. Cepstral measures in the assessment of severity of voice disorders. CoDAS. 2019;31.

Essa ferramenta gera um relatório com informações e imagens referentes aos domínios do tempo, frequência, tempo-frequência, e quefrência, bem como valores de medidas acústicas relacionadas a f0, medidas de período, medidas de perturbação do período da f0, medidas de perturbação de amplitude da f0, medidas espectrais, medidas de ruído glotal e medidas cepstrais.

No relatório acústico do VoxMore são gerados quatro arquivos com as seguintes informações: Arquivo I contém oscilogramas do sinal de voz e traçados da f0 e intensidade; Arquivo II apresentadas imagens relacionadas ao domínio da frequência, espectro de Fourier e espectro de LPC, e ao domínio do tempo-frequência, espectrograma; Arquivo III apresenta informações sobre a análise cepstral e cepstrograma; Arquivo IV mostra os valores de todas as medidas acústicas, no formato de resultados numéricos e em gráficos de barras verticais.
#
## Instalar
Para instalar o VoxMore, o download do arquivo deve ser feito pelo link:
https://github.com/abreusamuel/VoxMore/blob/main/plugin_VoxMore.zip. Será baixado um arquivo
compactado, o qual deve ser descompactado na pasta de preferências do Praat. Para
localizar essa pasta, deve ser observado o sistema operacional utilizado no
computador, pois cada sistema operacional utiliza caminhos diferentes, conforme
descrição abaixo (considerar user_name como nome do usuário utilizado no sistema
operacional):
* Linux: /home/user_name/.praat-dir
* Mac: /Users/user_name/Library/Preferences/Praat Prefs/
* Windows: C:\Users\user_name\Praat

Vale ressaltar que, se o Praat estiver aberto no momento da instalação do plugin, será
necessário encerrar e iniciar novamente o Praat para que a instalação do VoxMore
funcione. Após a instalação concluída, o VoxMore estará disponível para ser acessado
no menu dinâmico do Praat.

#### Passos para instalar no Windows:
1. Após o download copiar ou recortar o arquivo plugin_VoxMore.zip

2. Localizar e abrir partição no Windows
<img src="/imagens/win1.png" width="600" height="300" />

3. Localizar e abrir pasta Usuários
<img src="/imagens/win2.png" width="600" height="300" />

4. Localizar e abrir pasta do seu usuário
<img src="/imagens/win3.png" width="600" height="300" />

5. Localizar e abrir pasta Praat
<img src="/imagens/win4.png" width="600" height="300" />

6. Colar e/ou descompactar o arquivo plugin_VoxMore.zip na pasta Praat
<img src="/imagens/win5.png" width="600" height="300" />


#
#### Créditos e Referências: 
#### Maryn Y, De Bodt M, Roy N. The Acoustic Voice Quality Index: toward improved treatment outcomes assessment in voice disorders. Journal of communication disorders. 2010; 43(3):161-174.
#### Latoszek BB, Maryn Y, Gerrits E, De Bodt M. The acoustic breathiness index (ABI): A multivariate acoustic model for breathiness. Journal of Voice. 2017; 31(4): 511-e11.

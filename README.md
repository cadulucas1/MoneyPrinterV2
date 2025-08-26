# MoneyPrinter V2

[![madewithlove](https://img.shields.io/badge/made_with-%E2%9D%A4-red?style=for-the-badge&labelColor=orange)](https://github.com/FujiwaraChoki/MoneyPrinterV2)

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donate-brightgreen?logo=buymeacoffee)](https://www.buymeacoffee.com/fujicodes)
[![GitHub license](https://img.shields.io/github/license/FujiwaraChoki/MoneyPrinterV2?style=for-the-badge)](https://github.com/FujiwaraChoki/MoneyPrinterV2/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/FujiwaraChoki/MoneyPrinterV2?style=for-the-badge)](https://github.com/FujiwaraChoki/MoneyPrinterV2/issues)
[![GitHub stars](https://img.shields.io/github/stars/FujiwaraChoki/MoneyPrinterV2?style=for-the-badge)](https://github.com/FujiwaraChoki/MoneyPrinterV2/stargazers)
[![Discord](https://img.shields.io/discord/1134848537704804432?style=for-the-badge)](https://dsc.gg/fuji-community)

> Follow me on [X](https://x.com/DevBySami).

Um aplicativo que automatiza o processo de ganhar dinheiro online.  
MPV2 (MoneyPrinter Versão 2) é, como o nome sugere, a segunda versão do projeto MoneyPrinter. É uma reescrita completa do projeto original, com foco em uma gama mais ampla de recursos e uma arquitetura mais modular.

> **Nota:** MPV2 precisa do Python 3.9 para funcionar corretamente.
> Assista ao vídeo no YouTube [aqui](https://youtu.be/wAZ_ZSuIqfk)

## Funcionalidades

- [x] Bot do Twitter (com CRON Jobs => `scheduler`)
- [x] Automatizador de Shorts do YouTube (com CRON Jobs => `scheduler`)
- [x] Marketing de Afiliados (Amazon + Twitter)
- [x] Encontrar empresas locais & prospecção a frio

## Versões

O MoneyPrinter tem diferentes versões para múltiplos idiomas, desenvolvidas pela comunidade para a comunidade. Aqui estão algumas versões conhecidas:
- Chinesa: [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)

Se você quiser enviar sua própria versão/fork do MoneyPrinter, abra uma issue descrevendo as alterações feitas no fork.

## Instalação

Por favor, instale primeiro o [Microsoft Visual C++ build tools](https://visualstudio.microsoft.com/de/visual-cpp-build-tools/) para que o CoquiTTS funcione corretamente.

> ⚠️Se você pretende entrar em contato com empresas coletadas por e-mail, instale primeiro a [Linguagem de Programação Go](https://golang.org/).

```bash
git clone https://github.com/FujiwaraChoki/MoneyPrinterV2.git

cd MoneyPrinterV2
# Copiar configuração de exemplo e preencher valores em config.json
cp config.example.json config.json

# Criar um ambiente virtual
python -m venv venv

# Ativar o ambiente virtual - Windows
.\venv\Scripts\activate

# Ativar o ambiente virtual - Unix
source venv/bin/activate

# Instalar os requisitos
pip install -r requirements.txt
```

## Uso

```bash
# Executar o aplicativo
python src/main.py
```

## Documentação

Todos os documentos relevantes podem ser encontrados [aqui](docs/).

## Scripts

Para facilitar o uso, existem alguns scripts no diretório `scripts` que podem ser usados para acessar diretamente a funcionalidade principal do MPV2, sem a necessidade de interação do usuário.

Todos os scripts devem ser executados a partir do diretório raiz do projeto, por exemplo: `bash scripts/upload_video.sh`.

## Contribuindo

Por favor, leia o [CONTRIBUTING.md](CONTRIBUTING.md) para detalhes sobre nosso código de conduta e o processo de envio de pull requests. Confira [docs/Roadmap.md](docs/Roadmap.md) para uma lista de funcionalidades que precisam ser implementadas.

## Código de Conduta

Por favor, leia o [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) para detalhes sobre nosso código de conduta e o processo de envio de pull requests.

## Licença

MoneyPrinterV2 está licenciado sob `Affero General Public License v3.0`. Veja [LICENSE](LICENSE) para mais informações..

## Agradecimentos

- [CoquiTTS](https://github.com/coqui-ai/TTS)
- [gpt4free](https://github.com/xtekky/gpt4free)

## Aviso Legal

Este projeto é apenas para fins educacionais. O autor não será responsável por qualquer uso indevido das informações fornecidas. Todas as informações neste site são publicadas de boa-fé e apenas para fins de informação geral. O autor não oferece garantias sobre a integridade, confiabilidade e precisão dessas informações. Qualquer ação que você tomar com base nas informações encontradas neste site (FujiwaraChoki/MoneyPrinterV2) é estritamente por sua conta e risco. O autor não será responsável por quaisquer perdas e/ou danos relacionados ao uso do nosso site.

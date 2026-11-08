<p align="center"><img src="robo-liquidacao-logo.svg" width="96" alt="Logo do Robô da Liquidação"></p>
<h1 align="center">Robô da Liquidação</h1>
<p align="center">DCF · Automação com conferência do operador</p>
<p align="center"><a href="https://github.com/diegodr-sudo/Robo-da-Liquidacao/releases/latest"><strong>Baixar a versão mais recente</strong></a></p>

## Instalar

| Seu computador | Arquivo para baixar |
|---|---|
| Windows 10/11 · 64 bits | Instalador com final `-setup.exe` |
| Mac com chip Apple (M1, M2, M3 ou posterior) | `.dmg` com `aarch64` no nome |
| Mac Intel | `.dmg` com `x64` no nome |

No Windows, execute o instalador. No Mac, abra a imagem DMG e arraste o Robô para **Aplicativos**. O instalador pode ser apagado depois. Não é necessário instalar Python ou Node.

Esta primeira versão ainda não tem certificado comercial do Windows nem notarização Apple. O sistema pode mostrar um aviso. No Mac, após tentar abrir, autorize em **Ajustes do Sistema → Privacidade e Segurança → Abrir Mesmo Assim**, se a política do computador permitir.

## Entrar e trabalhar

O download é público. **O acesso ao Robô exige uma conta ativa da equipe.**

O Robô aproveita a configuração local do AutoLiquid, quando disponível. Em um computador novo, peça os dados de conexão ao administrador. Eles ficam apenas na pasta de dados deste computador e não acompanham os instaladores.

As automações utilizam o navegador de automação e os sistemas externos autenticados pelo operador. O OCR de PDFs digitalizados requer Tesseract e o idioma inglês. Confira os resultados antes de registrar no SIAFI.

## Atualizar

O Robô avisa quando houver uma nova versão. Em **Configurações → Atualizações**, leia as novidades e escolha **Atualizar e reiniciar**. Finalize as operações antes de atualizar.

Cada atualização tem uma assinatura verificada pelo aplicativo. Suas configurações e dados ficam separados do programa e são preservados:

- Windows: `%APPDATA%\Robo da Liquidacao`.
- Mac: `~/Library/Application Support/Robo da Liquidacao`.

## Sobre este repositório

Este espaço contém somente os instaladores, notas de versão e informações de uso. O código do aplicativo fica em um repositório privado. Documentos de trabalho, bancos de dados, credenciais e chaves privadas não são distribuídos aqui.

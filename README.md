# Pharaf

Servidor particular de voz, chat e compartilhamento de tela. Este repositório guarda só os instaladores.

## Baixar

Vá em **[Releases → a versão mais nova](https://github.com/Isaac-GhostLolp/pharaf-releases/releases/latest)** e baixe o arquivo do seu sistema:

| Sistema | Arquivo |
|---|---|
| **Windows** | `Pharaf-Setup-x.y.z.exe` |
| Linux (qualquer distro) | `Pharaf-x.y.z.AppImage` |
| Linux (Ubuntu/Debian) | `Pharaf-x.y.z.deb` |

### Windows

Abra o `Pharaf-Setup-….exe`. Como o programa não tem assinatura digital (que é paga), o Windows vai mostrar
**"O Windows protegeu o computador"**: clique em **Mais informações → Executar assim mesmo**.
A instalação é só para o seu usuário e não pede administrador.

### Linux

- **AppImage**: dê permissão de execução (`chmod +x Pharaf-*.AppImage`) e abra.
- **.deb**: `sudo apt install ./Pharaf-*.deb`.

## Atualizações

O programa se atualiza sozinho: quando sai uma versão nova, aparece um botão verde **Atualizar** no canto de cima.
(No `.deb` ele só avisa, porque instalar precisa de `sudo`.)

Para conferir um download: `sha256sum -c SHA256SUMS.txt`.

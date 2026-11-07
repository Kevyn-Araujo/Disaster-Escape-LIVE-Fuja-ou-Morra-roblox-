# External Lab — pacotes para download

Aplicativo C++20, ImGui e DirectX 11 com ESP e coleta automática em um **simulador com dados mock**. Não se conecta ao Fortnite, não detecta entidades de partidas reais e não envia comandos ao jogo.

## Downloads

- [Código-fonte completo (.zip)](https://raw.githubusercontent.com/Kevyn-Araujo/Disaster-Escape-LIVE-Fuja-ou-Morra-roblox-/main/fortnite-external/fortnite_external_source.zip)
- [Executáveis Windows x64 (.zip)](https://raw.githubusercontent.com/Kevyn-Araujo/Disaster-Escape-LIVE-Fuja-ou-Morra-roblox-/main/fortnite-external/fortnite_external_windows_x64.zip)

Extraia o pacote Windows e execute `fortnite_external.exe`. Insert mostra/esconde o menu; F8 é a parada de emergência. A coleta é habilitada em Auto Farm e atua somente na simulação.

O pacote de código contém CMake, dependências vendorizadas, testes, instruções do Visual Studio 2022 e documentos de arquitetura/integração/validação.

## Validação

17/17 grupos de testes comportamentais passaram no Linux, incluindo ASan/UBSan. Compilação e link Windows x64 passaram com LLVM-MinGW. A interface gráfica e os executáveis não foram executados em Windows nesta entrega. Integração real com Fortnite não implementada.

## SHA-256

```text
c460bce89d0271bc092386fea3aa48034a838d17284130d0c7892d3831c08c7a  fortnite_external_source.zip
37827b07461dd2db72344ad9e67a82b6700adccc08bda8c18072e3bc0a01a359  fortnite_external_windows_x64.zip
```

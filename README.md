## Aviso Legal

Este guia é destinado apenas para fins educacionais. O uso de técnicas de phishing para captura de senhas é ilegal e viola as leis de privacidade e segurança. O autor não se responsabiliza pelo uso indevido dessas informações. Pratique a segurança digital de maneira ética e legal.


# Phishing para Captura de Senhas do Google

## Descrição

Este projeto tem como objetivo fornecer uma abordagem básica sobre a execução de phishing para captura de senhas do Google utilizando a ferramenta setoolkit no ambiente Kali Linux. É crucial destacar que o uso deste tipo de técnica é ilegal e viola as políticas éticas e legais. Este guia é fornecido apenas para fins educacionais e de conscientização.

**Ferramentas Utilizadas:**
- Kali Linux
- setoolkit

## Configurando o Ambiente

1. **Acesso Root:**
   - Execute o seguinte comando para obter acesso root:
     ```
     sudo su
     ```

2. **Iniciando o setoolkit:**
   - Inicie a ferramenta setoolkit com o comando:
     ```
     setoolkit
     ```

## Configurando o Phishing

1. **Tipo de Ataque:**
   - Selecione "Social-Engineering Attacks" no menu principal.

2. **Vetor de Ataque:**
   - Escolha "Web Site Attack Vectors" para iniciar um ataque baseado na web.

3. **Método de Ataque: Credential Harvester:**
   - Selecione "Credential Harvester Attack Method" para realizar a captura de credenciais.

4. **Método de Ataque: Web Templates:**
   - Escolha "Web Templates" como método de ataque.

5. **Obtendo o Endereço da Máquina:**
   - Utilize o comando `ifconfig` para identificar o endereço IP da máquina.

6. **Selecionando o Template:**
   - Escolha o template desejado para a página de phishing. Exemplo: "Google."

7. **Configurações Adicionais:**
   - Siga as instruções fornecidas pela ferramenta para configurar o ataque, como escolher o site alvo e configurar os parâmetros.


# Cotação do Dólar

Aplicativo Android desenvolvido em Kotlin para a matéria **Programação para Dispositivos Móveis**. O projeto consiste no consumo de uma API REST pública para buscar a cotação atual do dólar e realizar a conversão de um valor em Reais (R$) para Dólares (US$).

## Funcionalidades
- Consulta do valor atual da cotação do dólar (USD para BRL) em tempo real utilizando uma API pública.
- Conversão aproximada de um valor em Reais para Dólares com base na cotação obtida.
- Gerenciamento de estado da interface (carregamento, exibição de resultados e mensagens de erro).
- Processamento em background para que a interface não trave durante a chamada de rede.

## Tecnologias utilizadas
- **Kotlin** — linguagem de programação.
- **Android Studio** — ambiente de desenvolvimento.
- **Jetpack Compose** — construção declarativa da interface.
- **Material 3** — componentes visuais da interface.
- **HttpURLConnection & org.json** — ferramentas nativas do Android/Java utilizadas para consumo de API REST e parsing do JSON.
- **Coroutines** — processamento assíncrono.
- **Gradle Kotlin DSL** — configuração e gerenciamento da compilação.

## Como executar
1. Clone o repositório:
```bash
git clone https://github.com/GabrieldeMoura9648/Cotacao_Dolar.git
```
2. Abra o Android Studio.
3. Selecione **Open** e escolha a pasta do projeto clonado.
4. Aguarde a sincronização do Gradle.
5. Execute o aplicativo em um emulador ou dispositivo Android compatível com acesso à internet.

## Estrutura do projeto
- `app/` — módulo principal do aplicativo Android, contendo a interface em Jetpack Compose (`MainActivity.kt`), o modelo de dados (`Cotacao.kt`) e o repositório que realiza o consumo da API (`CotacaoRepository.kt`).
- `gradle/` — arquivos de suporte ao Gradle e ao gerenciamento de versões.
- `build.gradle.kts` e `settings.gradle.kts` — configurações de construção do projeto.

## Contexto acadêmico
Repositório desenvolvido como atividade prática da disciplina **Programação para Dispositivos Móveis**, com foco no consumo nativo de APIs REST e manipulação de respostas JSON via `HttpURLConnection`, operando dentro de Coroutines para requisições de rede no Android.

---
Desenvolvido por [Gabriel de Moura](https://github.com/GabrieldeMoura9648).

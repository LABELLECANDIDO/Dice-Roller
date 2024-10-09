# Dice Roller

## Descrição

O **Dice Roller** é um aplicativo Android simples que simula o lançamento de um dado de seis lados. Ele utiliza a biblioteca Jetpack Compose para a interface do usuário e permite que o usuário veja a face do dado após cada lançamento.

## Funcionalidades

- Exibe uma imagem do dado correspondente ao número gerado aleatoriamente.
- Permite que o usuário "role" o dado ao pressionar um botão.
- A interface é construída utilizando o Jetpack Compose, proporcionando uma experiência moderna e responsiva.

## Tecnologias Utilizadas

- **Kotlin**: Linguagem de programação principal para o desenvolvimento Android.
- **Jetpack Compose**: Ferramenta para construir interfaces de usuário de forma declarativa.
- **Android Studio**: IDE para desenvolvimento Android.

## Estrutura do Projeto

O código-fonte principal está localizado no arquivo `MainActivity.kt`. Aqui está um resumo da estrutura:

```kotlin
package com.example.diceroller

import android.os.Bundle
import androidx.activity.ComponentActivity
import androidx.activity.compose.setContent
import androidx.compose.foundation.Image
import androidx.compose.foundation.layout.Column
import androidx.compose.foundation.layout.Spacer
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.foundation.layout.height
import androidx.compose.foundation.layout.wrapContentSize
import androidx.compose.material3.Button
import androidx.compose.material3.MaterialTheme
import androidx.compose.material3.Surface
import androidx.compose.material3.Text
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.Alignment
import androidx.compose.ui.Modifier
import androidx.compose.ui.res.painterResource
import androidx.compose.ui.res.stringResource
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.unit.dp
import androidx.compose.ui.unit.sp
import com.example.diceroller.ui.theme.DiceRollerTheme
```

## Principais Componentes
- MainActivity: Atividade principal que configura o tema e exibe a interface do usuário.
- DiceWithButtonAndImage: Função composable que exibe a imagem do dado e o botão para rolá-lo.

## Como Usar

### Pré-requisitos

Certifique-se de ter o [Android Studio](https://developer.android.com/studio) instalado em seu computador.

### Clone o Repositório

Para obter o código-fonte do projeto, execute o seguinte comando no seu terminal:

```bash
git clone https://github.com/seuusuario/DiceRoller.git

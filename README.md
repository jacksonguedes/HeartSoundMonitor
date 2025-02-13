Este projeto foi desenvolvido no âmbito da disciplina de Informática Industrial do curso de engenharia elétrica da UFCG.

# HeartSound Monitor

## Descrição do Projeto

O HeartSound Monitor é um sistema inovador de monitoramento cardíaco baseado na análise de áudio. Ele permite a captura e o processamento de sons cardíacos, facilitando a identificação de possíveis anomalias de forma rápida e acessível. O sistema é voltado para médicos, pacientes e administradores de saúde, permitindo tanto o monitoramento domiciliar quanto a análise profissional dos dados coletados.

## Objetivo

Desenvolver uma solução eficiente para a captura, processamento e análise de sons cardíacos utilizando técnicas avançadas de processamento de sinais e aprendizado de máquina. O sistema fornecerá diagnósticos preliminares e auxiliará na tomada de decisão médica.

## Funcionalidades
Principais Funcionalidades

- Captura de Áudio Cardíaco – Coleta de sons do coração através de estetoscópios digitais ou dispositivos específicos.
- Análise e Processamento – Uso de técnicas de transformada de Fourier (FFT) para extrair padrões e identificar anomalias.
- Monitoramento Remoto – Armazenamento de dados para acesso e análise posterior por médicos e pacientes.
- Geração de Relatórios – Produção automática de relatórios detalhados sobre a saúde cardíaca do paciente.
- Interface Amigável – Aplicativo móvel e dashboard para fácil visualização dos dados e interações com o sistema.

## Público-Alvo

- Médicos – Acompanham a saúde cardíaca de pacientes e geram relatórios baseados na análise dos sons cardíacos.
- Pacientes – Monitoram seus batimentos cardíacos em casa e compartilham dados com profissionais de saúde.
- Administradores – Gerenciam usuários, acessos e configuração do sistema.

## Tecnologias Utilizadas

- Linguagens: Python, JavaScript
- Frameworks: Flask/Django (Backend), React (Frontend)
- Banco de Dados: PostgreSQL/MySQL
- Processamento de Áudio: NumPy, SciPy, Librosa

## Fluxo de Funcionamento

1️- O médico ou paciente captura o som cardíaco usando um dispositivo de captura.

2️- O áudio é enviado para o servidor, onde passa por processamento e análise.

3️- O sistema aplica algoritmos para detectar possíveis anomalias.

4️- Os resultados são armazenados no banco de dados e disponibilizados no aplicativo e no dashboard.

5️- O médico pode acessar relatórios detalhados para avaliação e diagnóstico.

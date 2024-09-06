# SANDBOX

**SANDBOX** é um projeto experimental que simula um mundo virtual habitado por IAs que se comportam como seres humanos. Utilizando **Rust** para a engine de IAs e **PyTorch** para desenvolvimento de redes neurais, o objetivo é criar um ambiente onde as IAs possam interagir e evoluir de acordo com regras e comportamentos predefinidos.

## Objetivo

O propósito do projeto é desenvolver um ambiente virtual onde várias IAs convivam e tomem decisões autônomas, simulando comportamentos humanos. Ao longo do tempo, essas IAs poderão evoluir em complexidade, interagindo entre si e com o ambiente ao redor.

## Tecnologias Utilizadas

- **Rust**: Linguagem principal para a criação da engine das IAs, utilizando threads para cada IA.
- **PyTorch**: Biblioteca para criar redes neurais que ajudarão as IAs a tomar decisões mais complexas.
- **tch-rs**: Bindings do PyTorch para Rust, permitindo o uso de deep learning dentro do ambiente Rust.

## Funcionalidades

- **Simulação em Tempo Real**: Cada IA executa em sua própria thread, permitindo simulações simultâneas.
- **Tomada de Decisão Baseada em Regras**: As IAs podem tomar decisões simples baseadas em estados como fome, energia, etc.
- **Redes Neurais**: Utilizando PyTorch, as IAs poderão aprender a tomar decisões mais avançadas com o tempo.

## Contribuindo

Sinta-se à vontade para abrir **issues** ou enviar **pull requests**! Discussões sobre novas ideias ou melhorias são bem-vindas.

## Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

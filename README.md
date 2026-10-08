# Da Operação Analógica ao Controle Computacional: Estudo de Caso da Transformação Digital da Cadeia de Frio em uma Empresa Avícola

Repositório contendo o código-fonte em LaTeX (padrão SBC) do Trabalho de Conclusão de Curso (TCC) apresentado ao Instituto Federal de Educação, Ciência e Tecnologia da Bahia (IFBA) como requisito parcial para a conclusão do curso de Sistemas de Informação.

---

## 📌 Sobre o Projeto

Este estudo de caso aborda a modernização da infraestrutura de refrigeração de uma empresa avícola, substituindo um sistema de controle eletromecânico analógico e reativo por uma arquitetura digital integrada baseada nos conceitos da **Indústria 4.0** e **Refrigeração 4.0**. 

A solução envolveu a implementação do software **Sitrad Pro**, controladores de temperatura (**TC900** e **LOG**) e conversores de comunicação (**TCP-485**) aplicados a **9 ambientes críticos** (câmaras frias, túneis de congelamento e contêineres de armazenamento). O projeto garantiu monitoramento em tempo real, mitigação de perdas de produtos e transição para práticas de manutenção preditiva.

---

## 🚀 Tecnologias e Ferramentas Utilizadas

* **Documentação & Escrita:** LaTeX (Template da SBC) editado via [Overleaf](https://www.overleaf.com/).
* **Supervisão e Automação:** Sitrad Pro (Full Gauge Controls).
* **Hardware de Controle:** Controladores TC900E Log e conversores TCP-485.
* **Infraestrutura:** Servidor dedicado Windows Server e rede estruturada cabo Cat6.

---

## 📂 Estrutura do Repositório

```text
├── main.tex                 # Arquivo principal do artigo em LaTeX
├── sbc.bst                  # Estilo de citação bibliográfica (SBC)
├── sbc-template.bib         # Base de dados bibliográfica (Referências)
├── sbc-template.sty         # Estilo de formatação do artigo
├── image/                   # Pasta contendo diagramas, arquiteturas e gráficos
│   ├── arquitetura_nova.png
│   ├── esquema_instalacao.png
│   ├── interface_sitrad.png
│   └── ...
└── README.md                # Documentação do projeto
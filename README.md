**Plano Alimentar Inteligente com Python**

Este projeto consiste em um sistema para gerar um plano alimentar inteligente com base em requisitos energéticos e nutricionais específicos, utilizando dados de alimentos e nutrientes.

## Funcionalidades

* **Gerar Plano Alimentar**: O sistema gera automaticamente um plano alimentar composto por refeições balanceadas em termos de grupos alimentares e valor nutricional.
* **Adaptação do Plano**: Caso o usuário não esteja satisfeito com uma refeição específica, o sistema permite realizar ajustes, como substituir ou modificar alimentos, mantendo as restrições nutricionais.

## Uso do Projeto

1. Certifique-se de ter Python instalado em seu ambiente.
2. Clone este repositório em sua máquina local:

```bash
git clone https://github.com/seu-usuario/plano-alimentar-inteligente.git
```

3. Certifique-se de ter os arquivos `alimentos.xlsx` e `alimento_nut_all.xlsx` contendo os dados dos alimentos e nutrientes.
4. Execute o script `plano_alimentar.py`:

```bash
python plano_alimentar.py
```

5. Siga as instruções apresentadas no terminal para inserir o valor médio de energia desejado e o limiar para aceitação de variação.
6. O sistema irá gerar uma refeição com base nos requisitos fornecidos. Você poderá aceitar ou rejeitar a refeição proposta e fazer ajustes conforme necessário.
7. O sistema irá exibir os alimentos e nutrientes do plano alimentar final.

## Estrutura do Projeto

* **plano\_alimentar.py**: O script principal que contém a lógica para gerar o plano alimentar inteligente.
* **alimentos.xlsx**: Planilha contendo os dados dos alimentos.
* **alimento\_nut\_all.xlsx**: Planilha contendo os dados dos nutrientes presentes nos alimentos.

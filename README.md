# SmartContract ERC20 – RCRCoin

Este repositório contém a implementação de um **Smart Contract ERC-20** desenvolvido em **Solidity**, como parte de uma atividade prática do curso **Programador Blockchain** da **DIO (Digital Innovation One)**.

O objetivo do projeto é demonstrar, de forma prática, os conceitos fundamentais de tokens ERC-20, deploy em rede local e interação com contratos inteligentes utilizando ferramentas amplamente adotadas no ecossistema Ethereum.

---

## 📌 Tecnologias Utilizadas

- **Solidity ^0.8.x**
- **Remix IDE**
- **Ganache (Blockchain local)**
- **MetaMask**
- **Ethereum Virtual Machine (EVM)**

---

## 📜 Sobre o Smart Contract

O contrato implementa um token ERC-20 básico chamado **RCRCoin**, contendo as funcionalidades essenciais definidas no padrão:

- `totalSupply`
- `balanceOf`
- `transfer`
- `approve`
- `allowance`
- `transferFrom`

O supply inicial é definido no momento do deploy e atribuído ao endereço responsável pela implantação do contrato.

### 🔹 Informações do Token

| Propriedade | Valor |
|------------|------|
| Nome | RCR Coin |
| Símbolo | RCR |
| Decimais | 18 |
| Supply Inicial | 10 RCR |

---

## 🧠 Objetivos Educacionais

Este projeto tem caráter **didático**, com os seguintes objetivos:

- Compreender o funcionamento de tokens ERC-20
- Praticar o desenvolvimento de Smart Contracts em Solidity
- Realizar deploy em uma blockchain local (Ganache)
- Interagir com contratos inteligentes via Remix e MetaMask
- Entender eventos, transações e mudanças de estado na blockchain

---

## 🚀 Como Executar o Projeto

### 1️⃣ Pré-requisitos

- Ganache instalado e em execução
- MetaMask configurado e conectado ao Ganache
- Acesso ao Remix IDE (https://remix.ethereum.org)

---

### 2️⃣ Deploy do Contrato

1. Abra o arquivo `RCRCoin.sol` no Remix
2. Compile o contrato usando o compilador Solidity ^0.8.x
3. Em **Deploy & Run Transactions**, selecione:
   - Environment: `Injected Provider - MetaMask` **ou** `Dev - Ganache Provider`
4. Certifique-se de que o campo **VALUE** esteja definido como `0`
5. Faça o deploy do contrato

---

### 3️⃣ Interação com o Contrato

Após o deploy, é possível:

- Consultar o supply total (`totalSupply`)
- Verificar saldo de contas (`balanceOf`)
- Transferir tokens (`transfer`)
- Autorizar terceiros (`approve`)
- Realizar transferências delegadas (`transferFrom`)

Todas as transações podem ser visualizadas diretamente no Ganache.

---

## ⚠️ Observações Importantes

- Este projeto **não foi auditado** e **não deve ser utilizado em produção**
- O contrato foi desenvolvido exclusivamente para fins de aprendizado
- O uso de redes públicas requer cuidados adicionais com segurança e otimização de gas

---

## 📚 Referências

- https://ethereum.org
- https://docs.soliditylang.org
- https://docs.openzeppelin.com/contracts
- https://remix.ethereum.org

---

## 👨‍💻 Autor

Projeto desenvolvido por **Ricardo Castilho Resende**  
Como parte do curso **Programador Blockchain – DIO**

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT.

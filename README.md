# Projecto NFT de Pokemon na blockchain

## Neste projeto foi feito uma batalha de pokemons NFT ERC-721 utilizando as ferramentas:
- Linguagem Solidity;
- Ganache <https://archive.trufflesuite.com/ganache/>;
- Remix IDE <https://remix.ethereum.org/>;
- Metamask (extenção para instalar no navegador);
- IPFS (uma rede P2P ou Ponto a Ponto onde eu posso hospedar arquivos na minha máquina e compartilhar com qualquer outra pessoa da rede, sem a necessidade de um servidor central);
- Imagens de pokemons;
  
## Etapas:
- Instalar o IPFS no computador
  - Realizar o upload das imagens dos pokemons no IPFS
  - Copiar os links das imagens ao importar para serem utilizados no deploy 
- Instalar o Ganache
- Implementar o NFT ERC721
- Publicação na blockchain
- Receber e enviar transações

## Passos:
1. Instalar a extenção Metamesk;
2. Criar um novo workspace chamado "NFT-DIO-POKEMON";
  - Alterar o port number para "8545" por ter outros projetos rodando
  - Alterar o "HARDFORK" para "London" para não evitar incompatibilidade no Remix
4. Criar uma nova rede no Metamesk "DIONetwork";
5. Conectar uma carteira no ambiente do Ganache para o Metamask importanto uma carteira pela chave privada;
6. No remix criar o arquivo "DIOCoin.sol"
7. Compilar, realizar o deploy e realizar os testes com a rede simulanda no "Ganache" conectada coma o gerenciador de carteira "Metamesk" 

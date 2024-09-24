# Projecto NFT de Pokemon na blockchain

## Neste projeto foi feito uma batalha de pokemons NFT ERC-721 utilizando as ferramentas:
- Linguagem Solidity;
- Ganache <https://archive.trufflesuite.com/ganache/>;
- Remix IDE <https://remix.ethereum.org/>;
- Metamask (extenção para instalar no navegador);
- IPFS (uma rede P2P ou Ponto a Ponto onde eu posso hospedar arquivos na minha máquina e compartilhar com qualquer outra pessoa da rede, sem a necessidade de um servidor central);
- Imagens de pokemons (bulbasaur, charmander, pikachu e squirtle);
  
## Etapas:
- Instalar o IPFS no computador
- Instalar o Ganache
- Implementar o NFT ERC721
- Realizar o Deploy
- Receber e enviar transações da batalha de pokemons

## Passos:
1. Instalar a extenção Metamesk;
2. Criar um novo workspace do Ganache chamado "NFT-DIO-POKEMON";
    - Alterar o port number para "8545" por ter outros projetos rodando
    - Alterar o "HARDFORK" para "London" para não evitar incompatibilidade no Remix
4. Criar uma nova rede no Metamesk "DIONetwork" utilizando "RPC SERVER
HTTP://127.0.0.1:8545";
    - Importar duas carteiras com as respectivas chaves privada do Ganache e nomear:
      - DIOAcc01: "0x5Ac84582Ca6457515e1c6F1a629f2d214622F62F"
      - DIOAcc02: "0x6175D8d7c54D580349F8ce4EFbd6DB09Bc49c474"
      - Conectar a conta "DIOAcc01" do Metamesk na IDE Remix 
7. No remix criar na pasta de contracts uma nova pasta chamada "DIOPokemonsNFT" e dentro criar o arquivo "PokeDIO.sol"
   - Implementar o NFT ERC721
   - Alterar o EVM Version para "London" conforme o Ganache
8. No software IPFS:
   - Realizar o upload das imagens dos pokemons no IPFS
   - Copiar os links das imagens ao importar para serem utilizados no deploy 
9. Compilar, realizar o deploy e realizar os testes com a rede simulanda no "Ganache" conectada coma o gerenciador de carteira "Metamesk"

## Funcionamento

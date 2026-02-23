# Island Adventure Game

A browser-based RPG adventure game with NFT integration, built using JavaScript, HTML5 Canvas, and Solidity smart contracts.

## Features
- **2D Adventure Gameplay:** Explore an island, battle monsters, and collect items.
- **NFT Integration:** Connect your Ethereum wallet to use Adventurer NFTs as in-game characters.
- **Battle System:** Turn-based combat with multiple monsters and attacks.
- **Audio & Visuals:** Retro-inspired graphics and sound effects.
- **Smart Contract:** ERC-721 Adventurer NFT contract for unique player characters.

## Project Structure
```
contracts/
  adventurer.sol         # Solidity smart contract for Adventurer NFTs

game/
  index.html            # Main HTML file
  index.js              # Game logic and rendering
  classes.js            # Sprite and game entity classes
  battleScene.js        # Battle system logic
  style.css             # Game styling
  helpers/
    attacks.js          # Attack definitions
    audio.js            # Audio assets and logic
    battleZones.js      # Battle zone map data
    collisions.js       # Collision map data
    monsters.js         # Monster definitions
    nft.js              # NFT wallet and contract integration
  audio/                # Audio files
  img/                  # Game images and sprites
```

## Getting Started
### Prerequisites
- Node.js and npm (for local server, if needed)
- MetaMask browser extension (for NFT features)
- Access to Ethereum Mainnet (for live NFT integration)

### Running the Game
1. Clone the repository:
   ```sh
   git clone https://github.com/kunalKumar-13/Game-Dev.git
   cd Game-Dev/game
   ```
2. Open `index.html` directly in your browser, or run a local server:
   ```sh
   npx serve .
   # or
   python -m http.server
   ```
3. Play the game! Connect MetaMask to use your Adventurer NFTs.

### NFT Smart Contract
- The Adventurer NFT contract is in `contracts/adventurer.sol`.
- Deploy to Ethereum Mainnet for full NFT functionality.
- Contract address (example): `0x4b8f5913f1dd81ae68ac8d332635cbb4c7436f2a`

## Technologies Used
- JavaScript (ES6)
- HTML5 Canvas
- CSS3
- Solidity (ERC-721)
- Web3.js
- Howler.js (audio)

## Credits
- Game inspired by classic RPGs and open-source game tutorials.
- NFT integration and contract based on OpenZeppelin standards.

## License
MIT License

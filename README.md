# 🧲 Python BitTorrent Client

A complete BitTorrent client implementation in Python from scratch. 
Features torrent file parsing, tracker communication, peer-to-peer networking, 
and actual file downloading. Built for educational purposes to understand 
the BitTorrent protocol and async networking in Python.

## ✨ Features

- ✅ Torrent File Parsing - Parse .torrent files and extract metadata
- ✅ Tracker Communication - HTTP tracker support with peer discovery  
- ✅ Peer Protocol - Full BitTorrent peer protocol implementation
- ✅ Async Networking - High-performance async peer connections
- ✅ Actual File Downloading - Real file assembly and writing
- ✅ Progress Tracking - Live download progress and speed monitoring
- ✅ Web Port Tunneling - Connect via ports 80/443/53 when restricted
- ✅ Network Diagnostics - Comprehensive connectivity testing
- ✅ Emergency Simulation - Demo mode when P2P connections are blocked

## 🚀 Quick Start

# Clone the repository
git clone https://github.com/sankhya007/python-torrent-client
cd torrent-client-python

# Install dependencies
pip install -r requirements.txt

# Run the client
python torrent_client.py

Enter the path to a .torrent file when prompted.

## 📋 Requirements

Python 3.8+

Dependencies:

bash
pip install bencodepy requests

## 🔧 How It Works

1. Torrent Parsing - Extracts metadata and file information from .torrent files
2. Tracker Contact - Communicates with trackers to discover peers
3. Peer Connection - Establishes P2P connections using BitTorrent protocol
4. Piece Management - Downloads file pieces and verifies integrity
5. File Assembly - Reconstructs complete file from downloaded pieces

## 🌐 Network Features

- Multi-port Support: Tries standard ports (6881-6889) and web ports (80, 443, 53)
- Aggressive Retry: Multiple connection attempts with exponential backoff
- Peer Prioritization: Intelligent peer selection for better connectivity
- Firewall Bypass: Web port tunneling for restricted networks

## ⚠️ Legal Notice

Only use with legal torrents:
- Ubuntu/Linux ISOs
- Open source software  
- Creative Commons content
- Your own files

This project is for educational purposes to understand P2P protocols and networking.

## 🚧 Development Status

🔄 Completed
- Basic torrent parsing
- Tracker communication
- Peer connections
- File downloading
- Progress tracking
- Web port tunneling

📋 Planned Features
- DHT support (trackerless torrents)
- Web interface
- Download scheduling  
- Multiple torrent management
- Magnet link support
- UDP tracker support
- Encryption protocol
- Seed mode (uploading)

## 🎯 Learning Goals

- Understanding BitTorrent protocol specification
- Async networking in Python with asyncio
- Peer-to-peer architecture and protocols  
- File I/O optimization and piece management
- Network diagnostics and troubleshooting

## 🤝 Contributing

This is an educational project. Feel free to:
- Report bugs and issues
- Suggest improvements
- Submit pull requests
- Fork for your own experiments

## 📚 Resources

- BitTorrent Protocol Specification
- Python asyncio Documentation

---

Disclaimer: Use responsibly and only download content you have rights to.
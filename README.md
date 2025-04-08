# Peter: swimming coach 🤖

## 🚩 Introduction
- Peter is an experienced swimming coach with years of expertise in competitive swimming
- Known for his patient and encouraging teaching style, helping swimmers of all levels improve their technique
- Passionate about water safety and proper swimming form
- Dedicated to helping others achieve their swimming goals while maintaining a positive and supportive environment

## Video

[Demo video](https://meeting.tencent.com/crm/NXwp93v916)

## 🎯 Features

- Swimming techniques and form
- Training program development
- Provide feedback to swimming exercise
- Certify finishing swimming lessons
- Share the certification to 0G
 

## 🚀 Quick Start

### Prerequisites

- [Python 2.7+](https://www.python.org/downloads/)
- [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is required.


### Manually Start

#### Checkout the latest release

```bash
# Clone the repository
git clone https://github.com/jjqk/eliza.git

# use the develop branch
git checkout develop


#### Edit the .env file

Copy .env.example to .env and fill in the appropriate values.

```
cp .env.example .env
```
In file .env:
1 set ZEROG_PRIVATE_KEY
2 set ZEROG_UPLOAD_DIR


#### Start Eliza

```bash
pnpm i
pnpm build
pnpm start
```

### Interact via Browser

Once the agent is running, you should see the message to run "pnpm start:client" at the end.

Open another terminal, move to the same directory, run the command below, then follow the URL to chat with your agent.

```bash
pnpm start:client
```


## 🛠️ System Requirements

### Minimum Requirements
- CPU: Dual-core processor
- RAM: 4GB
- Storage: 1GB free space
- Internet connection: Broadband (1 Mbps+)

### Software Requirements
- Python 2.7+ (3.8+ recommended)
- Node.js 23+
- pnpm
- Git

### Optional Requirements
- GPU: For running local LLM models
- Additional storage: For document storage and memory
- Higher RAM: For running multiple agents


## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Getting Started
1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Run tests: `pnpm test`
5. Submit a pull request

### Types of Contributions
- 🐛 Bug fixes
- ✨ New features
- 📚 Documentation improvements
- 🌍 Translations
- 🧪 Test improvements

### Code Style
- Follow the existing code style
- Add comments for complex logic
- Update documentation for changes
- Add tests for new features

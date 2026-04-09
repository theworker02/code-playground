# Getting Started with MGL

## Prerequisites
- Node.js >= 18
- npm >= 9

## Install

```bash
git clone https://github.com/theworker02/mgl
cd mgl
npm install
npm run dev
```

Open http://localhost:5173

## Your First Pipeline

```mgl
data = read("users.csv")
adults = data.filter(age > 18)
print(adults)
```

Press ⌘+Enter to run.
# ⚙️ Installation Guide

Follow these steps to set up **Canvasly** locally on your machine.

---

## 1. Clone the Repository

```bash
git clone https://github.com/Binary0023/canvasly.git
cd canvasly
```

---

## 2. Install Dependencies

Using **npm**:

```bash
npm install
```

Or using **yarn**:

```bash
yarn install
```

Or with **pnpm**:

```bash
pnpm install
```

Or with **bun**:

```bash
bun install
```

---

## 3. Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Now open 👉 [http://localhost:3000](http://localhost:3000) in your browser to see Canvasly running. 🎉

---

## 4. Build for Production

```bash
npm run build
npm start
```

---

## 5. Environment Setup (Optional)

You can create a `.env.local` file in the root directory for custom configuration. Example:

```env
NEXT_PUBLIC_APP_NAME=Canvasly
NEXT_PUBLIC_API_URL=http://localhost:3000/api
```

---

✅ You’re all set! Next, check out the [Tutorials](tutorials.md) to learn how to create your first Canvasly project.

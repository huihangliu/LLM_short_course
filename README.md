# Large Language Models (LLM) - Comprehensive Principles and Training Guide

A comprehensive short course covering the principles and training methods of Large Language Models, including Pre-training, Supervised Fine-tuning (SFT), Reinforcement Learning from Human Feedback (RLHF), and Reinforcement Learning from Verifiable Rewards (RLVR).

🌐 **Live Slide**: [https://huihangliu.github.io/LLM_short_course/](https://huihangliu.github.io/LLM_short_course/)

## ✨ Features

- **Comprehensive Coverage**: From LLM foundations to advanced training techniques
- **Visual Learning**: Rich diagrams and illustrations for complex concepts
- **Responsive Design**: Optimized for both desktop and mobile viewing

## 📚 Content Overview

1. **LLM Foundations**
   - What are Large Language Models
   - Tokenization and embeddings
   - Transformer architecture

2. **Pre-training**
   - Language modeling objectives
   - Training data and scale

3. **Supervised Fine-tuning (SFT)**
   - Task-specific adaptation
   - SFT vs Pre-training comparison

4. **Reinforcement Learning from Human Feedback (RLHF)**
   - Why RLHF?
   - Reward modeling
   - InstructGPT methodology
   - Human preference learning
   - PPO (Proximal Policy Optimization)
   - DPO (Direct Preference Optimization)

5. **Reinforcement Learning from Verifiable Rewards (RLVR)**
   - Why RLVR?
   - GRPO (Group Relative Policy Optimization)
   - GxPO variants overview

6. **AI-Generated Content Detection**
   - AI-generated text detection
   - AI-generated image detection
   - AI-generated audio detection
   - AI-generated video detection

7. **Advanced Topics**
   - Challenges and future directions
   - Safety and evaluation
   - Open source ecosystem

## 🚀 Quick Start

### 🌐 Live Slides

🌐 **Live Slide**: [https://huihangliu.github.io/LLM_short_course/](https://huihangliu.github.io/LLM_short_course/)

### 🔧 Want to Contribute or Deploy Locally?

#### Step 1: Fork the Repository

1. Navigate to [https://github.com/noncollapse/LLM_short_course](https://github.com/noncollapse/LLM_short_course)
2. Click the **Fork** button in the top-right corner


#### Step 2: Clone Your Fork

```bash
# Clone your forked repository
git clone https://github.com/YOUR_USERNAME/LLM_short_course.git

# Navigate to the project directory
cd LLM_short_course
```

Replace `YOUR_USERNAME` with your GitHub username.

#### Step 3: Prerequisites

Make sure you have the following installed:
- Node.js >= 14 ([Download here](https://nodejs.org/))
- npm (comes with Node.js) or yarn

Check your installation:
```bash
node --version
npm --version
```

#### Step 4: Install Dependencies

```bash
npm install
```

This will install all required packages including Slidev, Vue.js, and other dependencies.

If macOS blocks a native dependency during build with an error like `ERR_DLOPEN_FAILED` or `library load disallowed by system policy`, clear the quarantine metadata once:

```bash
xattr -dr com.apple.quarantine /path/to/LLM_short_course-main
```


#### Step 5: Local Development

Start the development server:

```bash
npm run dev
```

This serves `slides.md`.

Then open [http://localhost:3030](http://localhost:3030) in your browser.

If port `3030` is already in use, run Slidev directly on another port:

```bash
npm run dev -- --port 3031
```

The development server supports:
- 🔥 Hot Module Replacement (HMR) - changes reflect instantly
- 📝 Live editing of `slides.md`
- 🎨 Real-time preview

#### Step 6: Make Your Changes

Edit `slides.md` to modify the presentation content.
The deck uses Markdown with extended Slidev syntax for slides, layouts, and components.



#### Step 7: Build for Production (Optional)

Create a local production build:

```bash
npm run build:local
```

This writes the static site to `dist/local/`.

To test that build locally, serve `dist/` with any static server, for example:

```bash
python3 -m http.server 4173 -d dist/local
```

If you are building for GitHub Pages under `/LLM_short_course/`, use:

```bash
npm run build
```

#### Step 8: Commit and Push Your Changes



#### Step 9: Deploy with GitHub Pages (Optional)

If you want to deploy your version to GitHub Pages:

1. Go to your forked repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select: **GitHub Actions**
4. The workflow in `.github/workflows/deploy.yml` will automatically handle deployment
5. Your site will be available at: `https://YOUR_USERNAME.github.io/LLM_short_course/`

#### Step 10: Create a Pull Request (Optional)

If you want to contribute your changes back to the original repository:

1. Go to your forked repository on GitHub
2. Click **Pull requests** → **New pull request**
3. Select the base repository: `noncollapse/LLM_short_course`
4. Add a title and description for your changes
5. Click **Create pull request**



## 📁 Project Structure

```
llm_short_course/
├── slides.md              # Main presentation content
├── figs/                  # Image assets
│   ├── InstructGPT.png
│   ├── grpo.png
│   ├── DPO.png
│   └── ...
├── package.json           # Dependencies and scripts
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions deployment
└── README.md
```

## 📖 Learn More

- [Slidev Documentation](https://sli.dev/)
- [Vue.js Guide](https://vuejs.org/guide/)
- [Markdown Guide](https://www.markdownguide.org/)

## 📝 License

This project is for educational purposes.
Original from [https://noncollapse.github.io/LLM_short_course](https://noncollapse.github.io/LLM_short_course)

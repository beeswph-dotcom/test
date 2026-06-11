unzip tiktok-content-nextjs.zip
cd tiktok-content-nextjs
npm install
cp .env.local.example .env.local
# ─────────────────────────────────────────────────────────
# TikTok Content System — Environment Variables
# Copy this file to .env and fill in your values
# ─────────────────────────────────────────────────────────

# Anthropic API Key (for local dev only — do NOT commit .env to git)
# Get yours at: https://console.anthropic.com/
VITE_ANTHROPIC_API_KEY=sk-ant-VCR CTR CVR GMV
# (Optional) Custom API proxy URL for production
# Replace the direct Anthropic calls in App.jsx with this endpoint
# VITE_API_PROXY_URL=https://your-backend.com/api/claude
npm run dev

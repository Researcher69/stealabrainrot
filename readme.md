# 🧠 Roblox Brainrot Server Joiner

A simple, beautiful web page that allows you to join Roblox servers using Place ID and Job ID.

## 🚀 Features

- ✅ Works on Mobile & Desktop
- ✅ Beautiful gradient UI
- ✅ Automatic Roblox app opening
- ✅ Fallback to browser if app doesn't open
- ✅ Error handling
- ✅ No backend needed - Pure HTML/CSS/JS

## 📱 Usage

Once deployed, use the following URL format:

```
https://your-domain.vercel.app/?placeId=139527221&jobId=abc123xyz
```

Parameters:
- `placeId` - The Roblox game Place ID (defaults to 139527221 - Steal a Brainrot)
- `jobId` - The server Job ID to join

## 🌐 Deploy to Vercel

1. Fork/Clone this repo
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your repository
5. Deploy!

Your joiner will be live at: `https://your-project.vercel.app`

## 💡 How It Works

1. User clicks the link with `?placeId=XXX&jobId=YYY`
2. Page extracts the parameters
3. Generates Roblox deep link: `roblox://experiences/start?placeId=XXX&gameInstanceId=YYY`
4. Attempts to open Roblox app
5. Provides fallback links if automatic opening fails

## 🎨 Customization

You can customize the look and feel by editing:
- Colors in the CSS gradients
- Text messages
- Icons
- Animations

Enjoy! 🎉

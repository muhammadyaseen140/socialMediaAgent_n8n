🤖 I built an AI agent that writes and publishes my social media posts for me!

Creating content for multiple platforms takes a lot of time, so I automated the whole process with n8n.

Here’s how it works:

📝 Form trigger: I enter a topic in a simple form.

🧠 AI Post Agent: it researches the topic using Tavily web search and writes the post with OpenAI.

🎨 Image Prompt Agent: a second agent turns the post into a detailed prompt for an image.

🖼️ Image generation: OpenAI creates a matching visual.

🚀 Auto-publishing: the post and image go live on LinkedIn, Facebook and Instagram.

What I learned:

- Building multi-agent workflows with tools and memory
- Connecting the Facebook Graph API and LinkedIn API
- Chaining AI steps so each agent’s output feeds the next

One input, three platforms, zero copy-pasting. 🙌

Next, I want to add an approval step so I can review each post before it goes live.
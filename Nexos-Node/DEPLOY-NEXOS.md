# Deploying Your Custom Nexos Proxy Node (For Free!)

Since GitHub Pages can only host static frontends (HTML/CSS), a true web proxy like Ultraviolet requires a backend **Node.js** server to parse requests and bypass blocks. 

I just generated the official source code for your custom proxy node in this folder (`Nexos-Node`). Here is exactly how to get it running on the internet for $0:

### Stop 1: Upload this folder to your GitHub
1. Create a new public repository on your GitHub account (e.g. `Nexos-Proxy`).
2. Upload all the files inside this `Nexos-Node` folder to that repository. 

### Step 2: Deploy for Free on Render
1. Go to [Render.com](https://render.com/) and create a free account.
2. Click **New +** and select **Web Service**. 
3. Connect your GitHub account and select your new `Nexos-Proxy` repository.
4. Render will auto-detect that it is a Node.js app! Give it a name, scroll down, and make sure the **Free Tier** is selected.
5. Click **Create Web Service**.

### Step 3: Link to Nexos!
Render will take a few minutes to build your node. Once it's live, Render will give you a custom URL (e.g. `https://nexos-proxy-xyz.onrender.com`).

1. Copy that URL.
2. Open Nexos `Main.html`, go to the **Web Proxy** tab.
3. Paste your shiny new Render URL into the *"Or paste custom proxy URL..."* box and hit **Enter**!

Now you own and operate your very own backend proxy node!

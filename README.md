<style>
    .profile-section {
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
        gap: 20px;
        max-width: 900px;
        margin: 0 auto;
        padding: 20px;
    }

    .text-section {
        flex: 1;
    }

    .text-section h1 {
        font-size: 2em;
        color: #ff4d4d;
        margin-bottom: 10px;
    }

    .text-section ul {
        list-style: none;
        padding-left: 0;
    }

    .text-section li {
        background: #1e1e1e;
        border-left: 5px solid #ff4d4d;
        padding: 10px 15px;
        margin: 10px 0;
        border-radius: 8px;
        font-family: sans-serif;
        transition: background 0.3s ease;
    }

    .text-section li:hover {
        background: #2a2a2a;
    }

    .profile-img {
        width: 300px;
        border-radius: 16px;
        box-shadow: 0 0 10px rgba(255, 77, 77, 0.5);
    }

    .spotify-widget {
        text-align: center;
        margin-top: 40px;
    }
</style>

<div class="profile-section">
    <div class="text-section">
        <h1>Hi Everyone</h1>
        <ul>
            <li>🔭 I'm currently figuring out what to specialize in</li>
            <li>👨‍🎓 I'm learning Vue/JS at the moment</li>
            <li>💬 Ask me about anything you want</li>
            <li>📫 How can you contact me? Add me on Discord: iNyix</li>
            <li>💼 I am currently unemployed.</li>
        </ul>
    </div>
    <img class="profile-img" src="https://nya-network.com/assets/inyix-pfp.png" alt="Profile Picture">
</div>

<div class="spotify-widget">
    <a href="https://github.com/iNyix">
        <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31fgciokdiwq27yvijoieth6hayy&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false&bar_color=ff0000&bar_color_cover=false" alt="spotify-github-profile">
    </a>
</div>

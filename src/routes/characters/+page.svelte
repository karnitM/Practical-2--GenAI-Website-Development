<section class="characters-container">
    <h1>Squid Game Characters</h1>

    <div class="character-grid">
        <a href="/characters/001" class="character-card">
            <img src="/images/001.jpg" alt="Oh Il-nam" />
            <h2>Oh Il-nam</h2>
            <p>Player 001</p>
        </a>

        <a href="/characters/067" class="character-card">
            <img src="/images/067.jpg" alt="Kang Sae-byeok" />
            <h2>Kang Sae-byeok</h2>
            <p>Player 067</p>
        </a>

        <a href="/characters/456" class="character-card">
            <img src="/images/456.jpg" alt="Seong Gi-hun" />
            <h2>Seong Gi-hun</h2>
            <p>Player 456</p>
        </a>
    </div>
</section>

<style>
    .characters-container {
        max-width: 900px;
        margin: 2rem auto;
        text-align: center;
        font-family: "Megrim", system-ui;
    }

    h1 {
        color: #e30a5a;
        font-size: 2.5rem;
        margin-bottom: 2rem;
    }

    .character-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 1.5rem;
        padding: 1rem;
    }

    .character-card {
        background: #ffe4ec;
        padding: 1rem;
        border-radius: 12px;
        text-decoration: none;
        color: black;
        box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .character-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 16px rgba(0,0,0,0.25);
    }

    .character-card img {
        width: 100%;
        border-radius: 10px;
        border: 3px solid #e30a5a;
        margin-bottom: 1rem;
    }

    .character-card h2 {
        margin: 0.5rem 0 0;
        font-size: 1.6rem;
        color: #e30a5a;
    }

    .character-card p {
        margin: 0;
        font-family: Arial, sans-serif;
        font-size: 1rem;
        color: #333;
    }
</style>

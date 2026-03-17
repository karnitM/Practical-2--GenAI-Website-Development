<section class="games-container">
    <h1>Squid Game Challenges</h1>

    <div class="games-grid">

        <div class="game-card">
            <h2>Red Light, Green Light</h2>
            <p>A deadly version of the children’s game where players must stop moving when the doll turns around.</p>
        </div>

        <div class="game-card">
            <h2>Tug of War</h2>
            <p>Teams compete in a high‑stakes tug of war where strategy matters as much as strength.</p>
        </div>

        <div class="game-card">
            <h2>Marbles</h2>
            <p>Players pair up and compete in any marble game they choose — the loser is eliminated.</p>
        </div>

        <div class="game-card">
            <h2>Glass Bridge</h2>
            <p>Contestants must cross a bridge made of tempered and normal glass, choosing each step carefully.</p>
        </div>

        <div class="game-card">
            <h2>Squid Game</h2>
            <p>The final challenge — a physical and strategic battle played on a squid‑shaped court.</p>
        </div>

    </div>
</section>

<style>
    .games-container {
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

    .games-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 1.5rem;
        padding: 1rem;
    }

    .game-card {
        background: #ffe4ec;
        padding: 1.5rem;
        border-radius: 12px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .game-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 16px rgba(0,0,0,0.25);
    }

    .game-card h2 {
        color: #e30a5a;
        margin-bottom: 0.5rem;
        font-size: 1.6rem;
    }

    .game-card p {
        font-family: Arial, sans-serif;
        font-size: 1rem;
        color: #333;
        line-height: 1.5;
    }
</style>

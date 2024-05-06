<script>
    import pfp from '../lib/img/pfp.jpg';
</script>


<body>
  <div class="container">
    <div class="card">
        <div class="card-header">
            <div class="card-icon">
                <img src="{pfp}" alt="">
            </div>
            <h2 style="color:var(--maroon); margin-top: 2rem;">kyuri</h2>
            <div class="seperator"></div>
            <div class="caption">
                FPS Aimer + Software Developer
            </div>
        </div>

        <div class="card-content">
            <ul>
                <li>Discord</li>
                <li>Twitter</li>
                <li>GitHub</li>
            </ul>
    </div>
  </div>

</body>

<style>
    @layer base {
    :global(:root){
    /** CSS DARK THEME PRIMARY COLORS */
    --color-primary-100: #382bf0;
    --color-primary-200: #5e43f3;
    --color-primary-300: #7a5af5;
    --color-primary-400: #9171f8;
    --color-primary-500: #a688fa;
    --color-primary-600: #ba9ffb;
    /** CSS DARK THEME SURFACE COLORS */
    --color-surface-100: #121212;
    --color-surface-200: #282828;
    --color-surface-300: #3f3f3f;
    --color-surface-400: #575757;
    --color-surface-500: #717171;
    --color-surface-600: #8b8b8b;
    /** CSS DARK THEME MIXED SURFACE COLORS */
    --color-surface-mixed-100: #1a1625;
    --color-surface-mixed-200: #2f2b3a;
    --color-surface-mixed-300: #46424f;
    --color-surface-mixed-400: #5e5a66;
    --color-surface-mixed-500: #76737e;
    --color-surface-mixed-600: #908d96;
    /** EXAMPLES */
    color: var(--color-primary-600);
    background-color: var(--color-surface-100);
    font-family: Arial, Helvetica, sans-serif;
  }
}




    body {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
        user-select: none;
    }

    .container {
        width: 100vw;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .card {
        width: 25rem;
        height: 32rem;
        border-radius: 1rem;
        background-color: var(--color-surface-mixed-100);
        outline: solid 1px var(--color-primary-300);
        box-shadow: 0 0 0.5rem 0.5rem var(--color-surface-mixed-200);
    }
    .card-header {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 10rem;
        background-color: var(--color-surface-mixed-100);
        border-radius: 1rem 1rem 0.5rem 0.5rem;
        outline: solid 1px var(--color-primary-300);
    }
    .card-icon {
        width: 6rem;
        height: 6rem;
        border-radius: 50%;
        background-color: var(--surface0);
        display: flex;
        align-items: center;
        justify-content: center;
        position: absolute;
        margin-bottom: 10rem;
        z-index: 1;
    }
    .card-icon img {
        width: 6rem;
        height: 6rem;
        border-radius: 50%;
        outline: solid 1px var(--color-primary-300);
    }
    .seperator {
        width: 80%;
        outline: solid 1px var(--color-primary-300);
    }
    .caption {
        width: 80%;
        margin-top: 1rem;
        text-align: center;
    }
    .card-content {
        display: flex;
        flex-direction: column;
        height: 50%;
        align-items: center;
        justify-content: space-evenly;
        border-radius: 0 0 1rem 1rem;
    }
    .card-content ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        text-align: center;
        gap: 1rem;
    }
    .card-content ul li {
        outline: 1px solid var(--color-primary-200);
        padding: 0.5rem 1rem;
        border-radius: 0.5rem;
    }
   
   
</style>
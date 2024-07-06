<script setup>

</script>

<template>
    <div class="body">
        <div class="header">
            <div>
                <h2>
                    Welander<span></span>
                </h2>
            </div>
            <div>
                <span id="center_styling"></span>
            </div>
            <div>
                <div class="contact">
                    <a href="#">Book a call</a>
                    <button>
                        <svg style="width: 20px;" fill="#000000" viewBox="0 0 24 24" id="turn-right-down-direction" data-name="Flat Line" xmlns="http://www.w3.org/2000/svg" class="icon flat-line" transform="matrix(1, 0, 0, -1, 0, 0)"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"><path id="primary" d="M19,18H6a1,1,0,0,1-1-1V3" style="fill: none; stroke: #F3F4F1; stroke-linecap: round; stroke-linejoin: round; stroke-width: 2;"></path><polyline id="primary-2" data-name="primary" points="16 21 19 18 16 15" style="fill: none; stroke: #F3F4F1; stroke-linecap: round; stroke-linejoin: round; stroke-width: 2;"></polyline></g></svg>
                        Let's connect
                    </button>
                </div>
            </div>
        </div>
        <div class="content">
            <div class="one">
                <p>New feature</p>
            </div>
            <div class="two">
                <h3>
                    miro
                </h3>
                <p>(Whitebording tool)</p>
            </div>
            <div class="three">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta tempore, alias illum et adipisci enim quibusdam, ipsam minima quia expedita perspiciatis beatae excepturi cum dolores ex animi possimus. Aspernatur, voluptatem!</div>
            <div class="four">                    <button>
                        <svg style="width: 20px;" fill="#000000" viewBox="0 0 24 24" id="turn-right-down-direction" data-name="Flat Line" xmlns="http://www.w3.org/2000/svg" class="icon flat-line" transform="matrix(1, 0, 0, -1, 0, 0)"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"><path id="primary" d="M19,18H6a1,1,0,0,1-1-1V3" style="fill: none; stroke: #F3F4F1; stroke-linecap: round; stroke-linejoin: round; stroke-width: 2;"></path><polyline id="primary-2" data-name="primary" points="16 21 19 18 16 15" style="fill: none; stroke: #F3F4F1; stroke-linecap: round; stroke-linejoin: round; stroke-width: 2;"></polyline></g></svg>
                        Let's connect
                    </button></div>
        </div>
    </div>
</template>


<style lang="scss" scoped>

.body {
    background-color: var(--base);
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            
}

button {
            background-color: var(--black); /* Green */
            border: none;
            color: var(--base);
            padding: 12px 20px;
            text-decoration: none;
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: space-around;
            gap: 5px;
            max-width: 200px;

            font-weight: 600;
        }


.header {
    background-color: var(--base);
    color: var(--black);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 150px;
    margin: 0;
    height: 10vh;

    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: bolder;

    h2 {
        text-transform: uppercase;
        letter-spacing: -5.3px;
        font-size: 32px;

        span {
            text-transform: lowercase;
        }
    }

    #center_styling {
        background-color: var(--black);
        display: block;
        width: 50px;
        height: 15px;
        border-radius: 15px;
    }

    .contact {
        
        display: flex;
        align-items: center;
        gap: 20px;
        justify-content: space-between;

        a {
            color: var(--black);
            text-decoration: none;
            word-spacing: -2px;
        }

    }
}

.content {
    padding: 100px 150px;
    max-width: 100vw;
    height: 150vh;
    display: flex;
    background-color: var(--base_dark);
    border-radius:  7vh 7vh 0 0;


    .one, .two, .three, .four {
        height: 100%;

    }

    .one {
        
        width: 20vw;
     
        border-radius:  7vh 0vh 0 0;
    }
    .two {
        
        width: 30vw;

  
    }
    .three {
        
        width: 30vw;


    }
    .four {
        display: flex;
        width: 20vw;
        border-radius: 0vh 7vh 0 0;
        flex-direction: column;
        flex-wrap: wrap;
        align-items: flex-end;
    }
}

</style>
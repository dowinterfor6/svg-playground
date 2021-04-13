<script>
  import { onMount } from "svelte";

  import { draw } from "svelte/transition";
  import { linear } from "svelte/easing";

  let show = false;

  onMount(() => {
    window.setTimeout(() => {
      show = true;
    }, 1000);
  });
</script>

<main>
  <section>
    {#if show}
      <svg
        xmlns:dc="http://purl.org/dc/elements/1.1/"
        xmlns:cc="http://creativecommons.org/ns#"
        xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
        xmlns:svg="http://www.w3.org/2000/svg"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
        xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
        width="1280"
        height="720"
        viewBox="0 0 338.66667 190.5"
        version="1.1"
        id="svg8"
        inkscape:version="1.0.2-2 (e86c870879, 2021-01-15)"
        sodipodi:docname="signature2.svg"
      >
        <g inkscape:label="Layer 1" inkscape:groupmode="layer" id="layer1">
          <path
            transition:draw={{ duration: 2000, easing: linear }}
            style="fill:none;stroke:#000000;stroke-width:0.264583px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
            d="M 65.179278,38.624758 C 27.563127,173.60035 57.583133,68.125686 36.210711,140.01474 c -2.141937,7.2047 -3.658241,14.59579 -6.03512,21.72643 -0.284498,0.85349 -1.207024,3.31371 -1.207024,2.41405 0,-30.06825 15.083568,-68.259064 24.140475,-96.561894 6.017371,-18.80429 7.885768,-34.826824 12.070236,-28.968568 2.526019,3.536426 18.456195,115.298832 13.27726,115.874272 -3.394213,0.37713 -33.796663,-8.15107 -33.796663,-12.07024 0,-2.05154 4.052842,-0.67842 6.035119,-1.20702 5.364245,-1.43047 47.689195,-16.23602 48.280947,-13.27726 0.717851,3.58926 -8.312238,39.83178 -4.828096,39.83178 0.914485,0 18.668275,-38.00772 27.761545,-41.03881 3.62482,-1.20827 8.86732,5.82604 10.86321,4.8281 0.72906,-0.36453 3.68555,-7.24214 2.41405,-7.24214 -7.88694,0 -13.02929,45.07089 -3.62107,41.0388 21.23231,-9.09956 15.66258,-107.482565 6.03512,-126.737482 -0.87376,-1.747517 -3.62108,3.382513 -3.62108,35.003684 0,24.21745 2.51233,50.410898 9.6562,73.628448 9.04704,29.40288 16.02415,-14.48429 24.14047,-14.48429 12.4575,0 21.26541,21.33582 37.41773,18.10536 11.60284,-2.32057 14.56219,-15.73026 24.14047,-20.5194 1.86919,-0.9346 33.71152,15.67711 41.0388,16.89833 18.24442,3.04073 36.09967,-1.20703 54.31607,-1.20703"
            id="path897"
          />
        </g>
      </svg>
    {/if}
  </section>
</main>

<style lang="scss">
  :global(*) {
    box-sizing: border-box;
  }

  :global(body) {
    height: 100vh;
    padding: 0;
    margin: 0;
  }

  :global(h1, h2, h3, h4, h5) {
    font-family: "Montserrat", sans-serif;
  }

  :global(p, span, div, ul, li) {
    font-family: "Roboto", sans-serif;
  }

  main {
    height: 100%;
    padding: 0;
    overflow: hidden;

    section {
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
</style>

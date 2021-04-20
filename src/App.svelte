<script>
  import { onMount } from "svelte";

  import { draw } from "svelte/transition";
  import { linear } from "svelte/easing";

  let show = false;
  let fill = false;

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
        xmlns:xlink="http://www.w3.org/1999/xlink"
        xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
        xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
        width="420px"
        height="594px"
        viewBox="0 0 210 297"
        version="1.1"
        id="svg8"
        inkscape:version="1.0.2-2 (e86c870879, 2021-01-15)"
        sodipodi:docname="dc-logo-redraw.svg"
      >
        <g inkscape:groupmode="layer" id="circle" inkscape:label="circle">
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="innerCircle"
            style="opacity:1;fill:none;fill-opacity:1;stroke:#000000;stroke-width:0.26458333;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 161.05965,81.770088 a 58.911102,58.811634 0 0 1 -58.9111,58.811632 58.911102,58.811634 0 0 1 -58.9111,-58.811632 58.911102,58.811634 0 0 1 58.9111,-58.811634 58.911102,58.811634 0 0 1 58.9111,58.811634 z"
          />
        </g>
        <g
          inkscape:groupmode="layer"
          id="innerDetail"
          inkscape:label="innerDetail"
        >
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="M 102.08641,26.796703 78.51155,130.77642 144.86688,47.322681 48.873573,93.721403 155.4922,93.567535 59.365374,47.446078 125.9613,130.70794 Z"
            id="septagramInnerLines"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="M 59.365374,47.446078 78.51155,130.77642 155.4922,93.567535 102.08641,26.796703 48.873573,93.721403 125.9613,130.70794 144.86688,47.322681 Z"
            id="septagramOuterLines"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            sodipodi:type="star"
            style="opacity:1;fill:none;fill-opacity:1;stroke:#000000;stroke-width:0.26458333;stroke-miterlimit:4;stroke-dasharray:none"
            id="septagram"
            sodipodi:sides="7"
            sodipodi:cx="102.16533"
            sodipodi:cy="81.476967"
            sodipodi:r1="54.680321"
            sodipodi:r2="49.265266"
            sodipodi:arg1="2.0181521"
            sodipodi:arg2="2.466951"
            inkscape:flatsided="true"
            inkscape:rounded="0"
            inkscape:randomized="0"
            d="M 78.51155,130.77642 48.873573,93.721405 59.365376,47.446077 102.08642,26.796703 l 42.78046,20.52598 10.62532,46.244852 -29.5309,37.140405 z"
            inkscape:transform-center-x="-0.017554083"
            inkscape:transform-center-y="-2.6904066"
          />
        </g>
        <g
          inkscape:groupmode="layer"
          id="innerTriangles"
          inkscape:label="innerTriangles"
          style="display:inline"
        >
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            sodipodi:type="star"
            style="opacity:1;fill:none;fill-opacity:1;stroke:#000000;stroke-width:0.2740161;stroke-miterlimit:4;stroke-dasharray:none"
            id="topTriangle"
            sodipodi:sides="3"
            sodipodi:cx="101.85464"
            sodipodi:cy="56.497494"
            sodipodi:r1="13.726504"
            sodipodi:r2="6.8632517"
            sodipodi:arg1="1.5707963"
            sodipodi:arg2="2.6179939"
            inkscape:flatsided="true"
            inkscape:rounded="0"
            inkscape:randomized="0"
            d="m 101.85464,70.223998 -11.887504,-20.589756 23.775004,-10e-7 z"
            inkscape:transform-center-y="3.5647017"
            transform="matrix(0.89753009,0,0,1.0387805,10.709708,-2.2258197)"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            sodipodi:type="star"
            style="opacity:1;fill:none;fill-opacity:1;stroke:#000000;stroke-width:0.2740161;stroke-miterlimit:4;stroke-dasharray:none"
            id="rightTriangle"
            sodipodi:sides="3"
            sodipodi:cx="101.85464"
            sodipodi:cy="56.497494"
            sodipodi:r1="13.726504"
            sodipodi:r2="6.8632517"
            sodipodi:arg1="1.5707963"
            sodipodi:arg2="2.6179939"
            inkscape:flatsided="true"
            inkscape:rounded="0"
            inkscape:randomized="0"
            d="m 101.85464,70.223998 -11.887504,-20.589756 23.775004,-10e-7 z"
            transform="matrix(0,-0.89753009,-1.0387805,0,185.34013,172.64766)"
            inkscape:transform-center-x="3.5647006"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            sodipodi:type="star"
            style="opacity:1;fill:none;fill-opacity:1;stroke:#000000;stroke-width:0.2740161;stroke-miterlimit:4;stroke-dasharray:none"
            id="bottomTriangle"
            sodipodi:sides="3"
            sodipodi:cx="101.85464"
            sodipodi:cy="56.497494"
            sodipodi:r1="13.726504"
            sodipodi:r2="6.8632517"
            sodipodi:arg1="1.5707963"
            sodipodi:arg2="2.6179939"
            inkscape:flatsided="true"
            inkscape:rounded="0"
            inkscape:randomized="0"
            d="m 101.85464,70.223998 -11.887504,-20.589756 23.775004,-10e-7 z"
            inkscape:transform-center-y="-3.5646982"
            transform="matrix(0.89753009,0,0,-1.0387805,10.709708,164.54513)"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            sodipodi:type="star"
            style="opacity:1;fill:none;fill-opacity:1;stroke:#000000;stroke-width:0.2740161;stroke-miterlimit:4;stroke-dasharray:none"
            id="leftTriangle"
            sodipodi:sides="3"
            sodipodi:cx="101.85464"
            sodipodi:cy="56.497494"
            sodipodi:r1="13.726504"
            sodipodi:r2="6.8632517"
            sodipodi:arg1="1.5707963"
            sodipodi:arg2="2.6179939"
            inkscape:flatsided="true"
            inkscape:rounded="0"
            inkscape:randomized="0"
            d="m 101.85464,70.223998 -11.887504,-20.589756 23.775004,-10e-7 z"
            transform="matrix(0,-0.89753009,1.0387805,0,19.069293,172.64766)"
            inkscape:transform-center-x="-3.5647014"
          />
        </g>
        <g
          inkscape:groupmode="layer"
          id="innerQuadrilaterals"
          inkscape:label="innerQuadrilaterals"
        >
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 70.422931,49.534775 10.44408,21.08709 20.390819,9.946743 -9.051534,-20.490288 z"
            id="topLeft"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 134.03513,49.534775 -10.44408,21.08709 -20.39082,9.946743 9.05153,-20.490288 z"
            id="topRight"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="M 70.422931,112.95838 80.867011,91.871291 101.25783,81.924548 92.206296,102.41484 Z"
            id="bottomLeft"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 134.03513,112.95838 -10.44408,-21.087089 -20.39082,-9.946743 9.05153,20.490292 z"
            id="bottomRight"
          />
        </g>
        <g
          inkscape:groupmode="layer"
          id="hangingQuadrilaterals"
          inkscape:label="hangingQuadrilaterals"
        >
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="leftSmall"
            style="fill:none;stroke:#000000;stroke-width:1.00000001;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 168.81641,490.27539 v 115.23828 l 25.14843,15.11328 V 508.78906 Z m -0.125,119.47266 0.0469,15.41601 25.04492,15.14649 0.13672,-15.2793 z"
            transform="scale(0.26458333)"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="rightSmall"
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 159.78607,129.7187 v 30.49012 l -6.65385,3.99873 V 134.6171 Z m 0.0331,31.61047 -0.0124,4.07882 -6.62646,4.00751 -0.0362,-4.04265 z"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="leftBig"
            style="fill:none;stroke:#000000;stroke-width:1.00000001;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 287.89258,570.4707 v 198.74805 l 33.22851,17.90234 -0.0117,-197.88476 z m -0.0176,203.77735 0.0957,33.64648 33.08203,17.10547 -0.0937,-32.61328 z m 0,39.28515 0.0957,34.68164 32.80078,18.70313 0.28125,-36.6543 z"
            transform="scale(0.26458333)"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="rightBig"
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 127.95802,150.93704 v 52.58542 l -8.79171,4.73666 0.003,-52.35701 z m 0.005,53.91609 -0.0253,8.9023 -8.75295,4.52582 0.0248,-8.62893 z m 0,10.39419 -0.0253,9.17619 -8.67854,4.94853 -0.0744,-9.69811 z"
          />
        </g>
        <g
          inkscape:groupmode="layer"
          id="hangingComplicated"
          inkscape:label="hangingComplicated"
        >
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="left"
            style="fill:none;stroke:#000000;stroke-width:1.00000001;opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="M 218.55469 527.9375 L 218.55469 668.14648 L 185.08398 692.68555 L 185.15039 709.30078 L 218.55469 720.29102 L 218.55469 725.60352 L 185.15039 714.55078 L 185.15039 730.36719 L 218.55469 741.42188 L 218.55469 746.37695 L 185.15039 735.28516 C 185.15039 735.28516 185.15128 782.78061 185.2832 806.92578 C 193.81459 815.98773 211.95338 819.47039 218.55469 820.16211 L 218.55469 855.62891 A 9.2794859 9.2794859 0 0 0 212.07812 864.47266 A 9.2794859 9.2794859 0 0 0 221.35742 873.75391 A 9.2794859 9.2794859 0 0 0 230.63672 864.47266 A 9.2794859 9.2794859 0 0 0 224.20508 855.64258 L 224.20508 820.17578 C 230.72066 819.50923 249.01281 816.03413 257.58789 806.92578 C 257.71964 782.78061 257.7207 735.28516 257.7207 735.28516 L 224.20508 746.41406 L 224.20508 741.45898 L 257.7207 730.36719 L 257.7207 714.55078 L 224.20508 725.64062 L 224.20508 720.32812 L 257.7207 709.30078 L 257.78711 692.68555 L 224.20508 668.06641 L 224.20508 527.9375 L 218.55469 527.9375 z "
            transform="scale(0.26458333)"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="right"
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 144.82609,139.68346 v 37.09696 l -8.85579,6.49263 0.0176,4.39611 8.83822,2.90784 v 1.4056 l -8.83822,-2.92438 v 4.18476 l 8.83822,2.92489 v 1.31103 l -8.83822,-2.9347 c 0,0 2.4e-4,12.5665 0.0351,18.95491 2.25726,2.39764 7.05649,3.31909 8.80308,3.50211 v 9.38393 a 2.4551973,2.4551973 0 0 0 -1.71359,2.33991 2.4551973,2.4551973 0 0 0 2.45515,2.45566 2.4551973,2.4551973 0 0 0 2.45515,-2.45566 2.4551973,2.4551973 0 0 0 -1.70171,-2.3363 v -9.38392 c 1.72391,-0.17636 6.56371,-1.09581 8.83254,-3.50573 0.0348,-6.38841 0.0351,-18.95491 0.0351,-18.95491 l -8.86768,2.94452 v -1.31103 l 8.86768,-2.93471 v -4.18476 l -8.86768,2.93419 v -1.4056 l 8.86768,-2.91765 0.0176,-4.39611 -8.88525,-6.51381 v -37.07578 z"
          />
          <path
            transition:draw={{ duration: 3000, easing: linear }}
            id="path transition:draw={{ duration: 3000, easing: linear }}916"
            style="fill:none;stroke:#000000;stroke-width:0.26458333;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1;stroke-miterlimit:4;stroke-dasharray:none"
            d="m 102.95946,271.0172 11.54852,-11.28351 -0.0455,11.77927 -11.56912,11.28206 m 0.0909,-54.56999 11.4473,-9.13643 0.0267,23.59739 -11.52367,11.3011 m -1.75136,17.03011 -11.548517,-11.28351 0.04547,11.77927 11.569117,11.28206 m -0.0909,-54.56999 -11.447291,-9.13643 -0.02667,23.59739 11.523661,11.3011 m -0.0432,-97.52688 v 11.4391 c -1.03956,0.35926 -1.736938,1.3382 -1.736841,2.43809 1.22e-4,1.0997 0.697461,2.07839 1.736841,2.43758 v 1.52446 c -1.03956,0.35925 -1.736938,1.3382 -1.736841,2.43809 1.22e-4,1.0997 0.697461,2.07838 1.736841,2.43758 v 1.52445 c -1.03956,0.35926 -1.736938,1.33821 -1.736841,2.4381 1.22e-4,1.0997 0.697461,2.07838 1.736841,2.43757 v 10.17303 l -11.418421,8.00984 v 6.29471 l 11.418421,8.86974 v 2.33991 l -11.441159,-8.45581 0.01035,4.72632 11.430824,9.03511 v 29.25403 l -11.480433,-11.14713 0.02066,13.03539 11.459769,11.38329 v 15.90082 L 89.694762,273.61004 v 6.68896 l 12.215818,11.2682 0.0945,0.0819 0.11682,-0.0907 12.36196,-11.33755 v -6.46692 l -11.5465,11.17957 v -15.90291 l 11.3962,-11.32024 0.0207,-13.03539 -11.41687,11.08563 v -29.24266 l 11.36726,-8.98498 0.0103,-4.72632 -11.3776,8.40878 v -2.34146 l 11.35538,-8.82116 v -6.29471 l -11.35538,-7.9654 v -10.24951 c 0.99395,-0.38413 1.64936,-1.33994 1.64951,-2.40553 6e-5,-1.06579 -0.65539,-2.02185 -1.64951,-2.40606 v -1.58853 c 0.99395,-0.38414 1.64936,-1.33994 1.64951,-2.40554 -1.5e-4,-1.06559 -0.65556,-2.0214 -1.64951,-2.40554 v -1.58853 c 0.99412,-0.38421 1.64957,-1.34027 1.64951,-2.40606 -1.5e-4,-1.06559 -0.65556,-2.0214 -1.64951,-2.40553 v -11.47166 z"
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

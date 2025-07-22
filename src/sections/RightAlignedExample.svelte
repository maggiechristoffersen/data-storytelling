<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
  <Scroller layout="right">
    {#snippet sticky()}
      <img
        src="detroit-worker.png"
        alt="An African-American worker assembling an airplane at Briggs Manufacturing Company in Detroit, Michigan."
        style="max-height: 60vh; width: auto; display: block; margin: 0 auto 1rem auto;"
      />
      <div
        class="image-text"
        style="text-align: center; margin-left: 10%; margin-right: 10%"
      >
        <p>
          <a style="color: #2E5339" href="https://www.loc.gov/item/2017690662/"
            >The above image shows a worker at Briggs Manufacturing Company in
            Detroit, Michigan assembling parts of an airplane as part of the war
            effort during the second world war.
          </a>
          This image was taken in 1942. <br /> <br />
          During this period, the wealth of Black Americans increased faster than
          it ever had.
          <a
            style="color: #2E5339"
            href="https://www.irp.wisc.edu/resource/the-great-black-migration-opportunity-and-competition-in-northern-labor-markets/"
          >
            While in 1940, Black men earned 40 cents for each dollar earned by
            white men, it increased by 1970 to 70 cents for each dollar.
          </a>
          The Black community's migration to higher-paying cities through the Great
          Migration allowed this increase to occur, though Black American's educational
          opportunities increased throughout this time as well.
        </p>
      </div>
    {/snippet}

    {#snippet scrolly()}
      <ArticleText>
        Between approximately 1910 and 1970, nearly six million Black Americans
        moved out of the American South into areas concentrated in the
        Northeast, Midwest, and Western areas of the United States.
      </ArticleText>

      <ArticleText>
        As the United States entered the first world war in 1917, numerous
        non-agricultural jobs were left available due to much of the workforce
        going abroad to fight in the war, and a decrease in European
        immigration.
      </ArticleText>

      <ArticleText>
        <p>Many Black Americans settled in Midwestern cities like Chicago,</p>

        <img
          src="slide1.jpg"
          alt="African-American apartments in Chicago, Illinois in 1941."
          style="width: 100%"
        />
        <p style="font-size: 0.8rem">
          <a
            style="color: #2E5339"
            href="https://loc.gov/pictures/resource/fsa.8a29902/"
          >
            African-American apartments in Chicago, Illinois in 1941.
          </a>
        </p>
      </ArticleText>

      <ArticleText>
        <p>Detroit,</p>
        <img
          src="slide2.jpg"
          alt="The Sojourner Truth Homes in Detroit, Michigan in 1942. The homes were built for Black defense industry workers during World War II."
          style="width: 100%"
        />
        <p style="font-size: 0.8rem">
          <a style="color: #2E5339" href="https://www.loc.gov/item/2017844920/">
            The Sojourner Truth Homes in Detroit, Michigan in 1942. The homes
            were built for Black defense industry workers during World War II.
          </a>
        </p>
      </ArticleText>

      <ArticleText>
        <p>and Cleveland.</p>
        <img
          src="slide3.jpg"
          alt="The Phyllis Wheatley association, a home for unmarried African-American women and girls established in Cleveland, Ohio, 1911."
          style="width: 100%;"
        />
        <p style="font-size: 0.8rem">
          <a
            style="color: #2E5339"
            href="https://digital-collections.columbuslibrary.org/digital/collection/postcard/id/11398"
          >
            The Phyllis Wheatley association, a home for unmarried
            African-American women and girls established in Cleveland, Ohio,
            1911.
          </a>
        </p>
      </ArticleText>
    {/snippet}
  </Scroller>
</div>

<style>
  .chart {
    width: 90%;
    margin: 0px auto;
  }
</style>

<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
  <Scroller layout="right">
    {#snippet sticky()}
      <img
        src="migrationseries.jpg"
        alt="Panel 1 of Jacob Lawrence's Migration Series"
        style="max-height: 60vh; width: auto; display: block; margin: 0 auto 1rem auto;"
      />
      <div style={"text-align: center; margin-left: 10%; margin-right: 10%"}>
        <p>
          <a
            href="https://en.wikipedia.org/wiki/File:Migration_Series_Panel_1.jpg"
            style={"color: #2E5339"}
          >
            The painting above features artist Jacob Lawrence's interpretation
            of the Great Migration.
          </a>
          One of sixty in a series, it displays the hardships of facing the choice
          of leaving one's home or continuing to live under strict Jim Crow laws.
          The series was created in 1941 and built on Lawrence's lived experience
          as the child of migrants from the Deep South.
        </p>
      </div>
    {/snippet}

    {#snippet scrolly()}
      <ArticleText>
        Despite seeking safety and a more well-heeled future, the racism sown in
        the United States seeped into Black communities in the Midwest. Often
        denied housing, loans, and other financial assistance, many Black
        families were pushed once again into restrictive financial conditions
        leaving them disadvantaged. The effects of these conditions, though many
        have been reconciled, are still felt today.
      </ArticleText>

      <ArticleText
        >Nonetheless, the Great Migration allowed many Black Americans to
        flourish away from the violence and trauma of the American South. <a
          style={"color: #2E5339"}
          href="https://www.strathmore.org/community-education/public-education/shades-of-blues/great-migration/"
          >Music</a
        >,
        <a
          style={"color: #2E5339"}
          href="https://www.npr.org/sections/codeswitch/2015/04/10/398806751/painting-the-epic-drama-of-the-great-migration-the-work-of-jacob-lawrence"
          >art</a
        >, and
        <a
          style={"color: #2E5339"}
          href="https://playbill.com/article/how-lorraine-hansberry-turned-her-familys-story-into-a-raisin-in-the-sun"
          >theatre</a
        > all thrived under newer, livelier conditions. Many communities like the
        Sojourner Truth Homes in Detroit and the predominantly Black neighborhoods
        in Chicago still exist today. Acknowledging the storied history of Black
        Americans in the United States leads to a deeper understanding of where,
        why, and what we are.
      </ArticleText>

      <ArticleText>
        <h2>Sources from Header Image</h2>
        <a
          style={"color: #2E5339"}
          href="https://clevelandmemory.contentdm.oclc.org/digital/collection/press/id/19618/rec/1"
          >Cleveland in 1944</a
        > <br />
        <a style={"color: #2E5339"} href="https://www.loc.gov/item/2017844899/"
          >The Streeter Family on their couch</a
        > <br />
        <a
          style={"color: #2E5339"}
          href="https://www.loc.gov/resource/hhh.il0034.photos/?sp=1"
          >Chicago in the 1930s</a
        > <br />
        <a
          style={"color: #2E5339"}
          href="https://www.loc.gov/resource/fsa.8d02799/"
          >Nursing school in Chicago in 1942</a
        > <br />
        <a
          style={"color: #2E5339"}
          href="https://www.loc.gov/resource/ppmsca.55827/"
          >Painting class in Chicago in 1942</a
        > <br />
        <a style={"color: #2E5339"} href="https://www.loc.gov/item/2017844894/"
          >Detroit in 1942</a
        >
      </ArticleText>
      <ArticleText>
        <h2>If you want to keep learning, try reading...</h2>
        <a style={"color: #2E5339"} href="https://www.ibramxkendi.com/stamped"
          >Stamped From The Beginning by Ibram X. Kendi</a
        > <br />
        <a
          style={"color: #2E5339"}
          href="https://www.bloomsbury.com/us/i-saw-death-coming-9781635576634/"
          >I Saw Death Coming by Kidada E. Williams</a
        > <br />
        <a style={"color: #2E5339"} href="https://1619books.com/"
          >The 1619 Project created by Nikole Hannah-Jones</a
        >
      </ArticleText>
    {/snippet}
  </Scroller>
</div>
<div>
  <img
    src="header.png"
    alt="A collage of historic photos related to the Great Migration"
  />
</div>

<style>
</style>

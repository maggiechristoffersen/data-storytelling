<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
  <Scroller layout="left">
    {#snippet sticky()}
      <img
        src="detroit-data.png"
        alt="The community vulnerability index of counties in Michigan, compared by their Black population."
        style={"max-width: 80vh; height: auto; display: block; margin: 0 auto 1rem auto;"}
      />
      <div style={"text-align: center; margin-left: 10%; margin-right: 10%"}>
        <p>
          <a
            href="https://blackwealthdata.org/explore/homeownership"
            style={"color: #2E5339"}
          >
            The above chart shows the social vulnerability index of counties in
            Michigan, compared by their Black population.
          </a>
          Wayne County, home to Detroit, has the highest community disaster risk
          by far, as well as the highest Black population.
          <br /> <br />
        </p>
        <p></p>
        <p>
          The social vulnerability index measures how likely a community is to
          be affected by events such as economic crises, health related issues,
          or natural disasters. It correlates greatly with rates of
          homeownership and wealth.
        </p>
      </div>
    {/snippet}

    {#snippet scrolly()}
      <ArticleText>
        <p>
          Black Americans fled the South for various reasons; violence, careeer
          opportunities, and promises of prosperity in the more northern locales
          of the United States all led Black families and individuals to move
          their entire lives to new locations.
        </p>
        <img
          src="chicago-family.jpg"
          alt="The Arthur family in Chicago, having moved there fleeing violence in Texas."
          style={"width: 100%"}
        />
        <p style={"font-size: 0.8rem"}>
          <a
            style={"color: #2E5339"}
            href="https://www.chicagotribune.com/2020/07/13/returning-south-a-family-revisits-a-double-lynching-that-forced-them-to-flee-to-chicago-100-years-ago/"
          >
            The Arthur family moved to Chicago in 1920, fleeing violence in
            their home state of Texas. Their sons were lynched in Paris, Texas,
            pushing the family to seek prosperity in the Midwest.
          </a>
        </p>
      </ArticleText>

      <ArticleText>
        <p>
          These families settled in the Midwest and created lives there. They
          found work, their children studied, and they began to grow a community
          in the new environment.
        </p>
        <img
          src="detroit-family.jpg"
          alt="The Streeter family in Detroit in 1942."
          style={"width: 100%"}
        />
        <p style={"font-size: 0.8rem"}>
          <a
            style={"color: #2E5339"}
            href="https://www.loc.gov/item/2017844899/"
          >
            The Streeter family lived in Detroit in the 1940s. The family
            eventually would move to the Sojourner Truth Homes in Detroit.
          </a>
        </p>
      </ArticleText>

      <ArticleText>
        <p>
          <a
            href="https://www.archives.gov/research/african-americans/migrations/great-migration"
            style={"color: #2E5339"}
          >
            However, localities began to implement restrictive laws that
            surpressed Black Americans' access to housing and created a pattern
            of redlining in American cities.
          </a>
          <a
            href="https://www.nytimes.com/2021/08/17/realestate/what-is-redlining.html"
            style={"color: #2E5339"}>Redlining</a
          >
          refers to a practice employed by the American government which deemed many
          predominantly Black neighborhoods as places where property values were
          most likelly to depreciate.
        </p>
        <img
          src="detroit-backlash.jpg"
          alt="A sign in Detroit reading 'We want white tenants in our white community.'."
          style={"width: 100%"}
        />
        <p style={"font-size: 0.8rem"}>
          <a
            style={"color: #2E5339"}
            href="https://www.loc.gov/item/2017844899/"
          >
            This sign was erected across from the Sojourner Truth Homes in
            Detroit, a housing project created for Black families in Detroit in
            the 1940s.
          </a>
        </p>
      </ArticleText>

      <ArticleText>
        In the 1980s, once Black Americans had settled in the Midwest, the ratio
        of their wages to their white counterparts <a
          style={"color: #2E5339"}
          href="https://journalistsresource.org/economics/inequality-labor-markets-politics-historical-basis-black-economic-fortunes/"
        >
          began to again fall, from 0.72 in the 70s to 0.69 in the 80s.</a
        >
        The gap continued on through the 20th and 21st centuries. Factors such as
        deindustrialization, a decrease in minimum wage, and declines in unionization
        all may play a role. However, recent studies suggest that
        <a
          style={"color: #2E5339"}
          href="https://journalistsresource.org/economics/inequality-labor-markets-politics-historical-basis-black-economic-fortunes/"
          >discriminatory hiring practices and the effects of the American
          criminal justice system
        </a> may have also played a great role.
      </ArticleText>
    {/snippet}
  </Scroller>
</div>

<style>
</style>

<script lang="ts">
  import SingleRating from './SingleRating.svelte';
  import Stars from './Stars.svelte';

  const companies = ['Reviews', 'Report Guru', 'BestTech'];
</script>

<section>
  <h2 class="visually-hidden">Ratings of Our Product</h2>
  {#each companies as company}
    <div>
      <Stars />
      <SingleRating {company} />
    </div>
  {/each}
</section>

<style>
  div {
    width: 100%;
    padding: 0.75rem;
    background-color: rgba(147, 123, 146, 0.2);
    margin-bottom: 0.75rem;
    border-radius: 0.5rem;
  }

  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }
</style>

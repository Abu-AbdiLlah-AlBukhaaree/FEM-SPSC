<script lang="ts">
  import Ratings from './components/rating-component/Ratings.svelte';
</script>

<main>
  <h1>10,000+ of our users love our products.</h1>
  <p>
    We only provide great products combined with excellent customer service. See
    what our satisfied customers are saying about our services.
  </p>

  <Ratings />
  <!-- 
      Rated 5 Stars in Reviews Rated 5 Stars in Report Guru Rated 5 Stars in BestTech Colton Smith Verified Buyer "We needed the same printed design as the one we had ordered a week prior. Not only did they find the original order, but we also received it in time. Excellent!" Irene Roberts Verified Buyer "Customer service is always excellent and very quick turn around. Completely delighted with the simplicity of the purchase and the speed of delivery." Anne Wallace Verified Buyer "Put an order with this company and can only praise them for the very high standard. Will definitely use them again and recommend them to everyone!"
   -->
</main>

<style>
  h1 {
    font-size: 3rem;
    font-weight: 700px;
    text-align: center;
    color: #4f214f;
    margin-bottom: 1.5rem;
  }

  p {
    font-size: 1.4rem;
    color: #937b92;
    text-align: center;
    line-height: 1.2;
    margin-bottom: 1.5rem;
  }
</style>

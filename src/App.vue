<script setup lang="ts"></script>

<template>
  <main>
    <article>
      <header class="title-container">
        <figure>
          <img src="/top-image.png" alt="Omelette" />
          <figcaption class="sr-only">Simple omelette recipe, ready in just 10 minutes</figcaption>
        </figure>
        <h1 class="text-preset-01 laterals">Simple Omelette Recipe</h1>
        <p class="text-preset-04 laterals">
          An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs
          cooked to perfection, optionally filled with your choice of cheese, vegetables, or meats.
        </p>
      </header>
      <section class="laterals preparation-time">
        <div>
          <h2 class="text-preset-03">Preparation time</h2>
          <ul>
            <li>
              <strong class="text-preset-04-bold">Total:</strong>
              <span class="text-preset-04">Approximately 10 minutes</span>
            </li>
            <li>
              <strong class="text-preset-04-bold">Preparation:</strong>
              <span class="text-preset-04">5 minutes</span>
            </li>
            <li>
              <strong class="text-preset-04-bold">Cooking:</strong>
              <span class="text-preset-04">5 minutes</span>
            </li>
          </ul>
        </div>
      </section>
      <section class="laterals">
        <h2 class="text-preset-02">Ingredients</h2>
        <ul>
          <li class="text-preset-04">2-3 large eggs</li>
          <li class="text-preset-04">Salt, to taste</li>
          <li class="text-preset-04">Pepper, to taste</li>
          <li class="text-preset-04">1 tablespoon of butter or oil</li>
          <li class="text-preset-04">
            Optional fillings: cheese, diced vegetables, cooked meats, herbs
          </li>
        </ul>
      </section>
      <section class="laterals">
        <h2 class="text-preset-02">Instructions</h2>
        <ol>
          <li class="text-preset-04">
            <strong class="text-preset-04-bold">Beat the eggs</strong>
            <p>
              In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed.
              You can add a tablespoon of water or milk for a fluffier texture.
            </p>
          </li>
          <li class="text-preset-04">
            <strong class="text-preset-04-bold">Heat the pan</strong>
            <p>Place a non-stick frying pan over medium heat and add butter or oil.</p>
          </li>
          <li class="text-preset-04">
            <strong class="text-preset-04-bold">Cook the omelette</strong>
            <p>
              Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure the
              eggs evenly coat the surface.
            </p>
          </li>
          <li class="text-preset-04">
            <strong class="text-preset-04-bold">Add fillings (optional)</strong>
            <p>
              When the eggs begin to set at the edges but are still slightly runny in the middle,
              sprinkle your chosen fillings over one half of the omelette.
            </p>
          </li>
          <li class="text-preset-04">
            <strong class="text-preset-04-bold">Fold and serve</strong>
            <p>
              As the omelette continues to cook, carefully lift one edge and fold it over the
              fillings. Let it cook for another minute, then slide it onto a plate.
            </p>
          </li>
          <li class="text-preset-04">
            <strong class="text-preset-04-bold">Enjoy</strong>
            <p>Serve hot, with additional salt and pepper if needed.</p>
          </li>
        </ol>
      </section>
      <section class="laterals">
        <h2 class="text-preset-02">Nutrition</h2>
        <p class="text-preset-04">
          The table below shows nutritional values per serving without the additional fillings.
        </p>

        <table>
          <caption class="sr-only">
            Nutritional values per serving without additional fillings.
          </caption>
          <thead class="sr-only">
            <tr>
              <th scope="col">Nutrient</th>
              <th scope="col">Amount</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row" class="text-preset-04-bold">Calories</th>
              <td class="text-preset-04">277kcal</td>
            </tr>
            <tr>
              <th scope="row" class="text-preset-04-bold">Carbs</th>
              <td class="text-preset-04">0g</td>
            </tr>
            <tr>
              <th scope="row" class="text-preset-04-bold">Protein</th>
              <td class="text-preset-04">20g</td>
            </tr>
            <tr>
              <th scope="row" class="text-preset-04-bold">Fat</th>
              <td class="text-preset-04">22g</td>
            </tr>
          </tbody>
        </table>
      </section>
    </article>
  </main>
</template>

<style scoped>
figure > img {
  width: 100%;
  max-height: 23.4375rem;
}

.title-container > h1 {
  color: var(--stone-900);
  margin-top: var(--spacing-500);
}

.title-container > p {
  color: var(--stone-600);
  margin-top: var(--spacing-300);
}

.preparation-time > div {
  padding: var(--spacing-300);
  background-color: var(--rose-50);
  border-radius: var(--spacing-150);
  display: flex;
  flex-direction: column;
  gap: var(--spacing-200);
}

.preparation-time > div > h2 {
  color: var(--rose-800);
}

.preparation-time > div > ul {
  display: flex;
  flex-direction: column;
  gap: var(--spacing-100);
}

.preparation-time ul {
  list-style: none;
}

.preparation-time li {
  color: var(--stone-600);
  display: flex;
  align-items: flex-start;
  gap: 8px;
}

.preparation-time li::before {
  content: "•";
  color: var(--rose-800);
  margin-right: 1rem;
  line-height: 1.5rem;
}

.preparation-time li::marker {
  color: var(--rose-800);
  margin-right: 0.75rem;
}
</style>

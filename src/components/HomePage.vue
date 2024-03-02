
<template>
    <main class="container">
        <div class="recipe">
            <img 
                class="image" 
                src="../assets/images/image-omelette.jpeg" 
                alt="A delicious recipe"
            />

            <h1 class="title">
                Simple Omelette Recipe
            </h1>

            <p class="subtitle">
                An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked 
                to perfection, optionally filled with your choice of cheese, vegetables, or meats.
            </p>

            <div class="preparation">
                <h2 class="preparation-title">
                    Preparation time
                </h2>

                <ul class="list">
                    <li class="list-item">
                        <div class="list-bullet" />

                        <div>
                            <span class="list-item-subtitle">Total: &nbsp;</span>Approximately 10 minutes
                        </div>
                    </li>
                    
                    <li class="list-item">
                        <div class="list-bullet" />

                        <div>
                            <span class="list-item-subtitle">Preparation: &nbsp;</span> 5 minutes
                        </div>
                    </li>
                    
                    <li class="list-item">
                        <div class="list-bullet" />

                        <div>
                            <span class="list-item-subtitle">Cooking: &nbsp;</span> 5 minutes
                        </div>
                    </li>
                </ul>
            </div>

            <div class="ingredients">
                <h2 class="title-medium">
                    Ingredients
                </h2>

                <ul class="list">
                    <li class="list-item">
                        <div class="list-bullet" />
                        
                        2-3 large eggs
                    </li>
                    
                    <li class="list-item">
                        <div class="list-bullet" />
                        
                        Salt, to taste
                    </li>
                    
                    <li class="list-item">
                        <div class="list-bullet" />
                        
                        Pepper, to taste
                    </li>
                    
                    <li class="list-item">
                        <div class="list-bullet" />
                        
                        1 tablespoon of butter or oil>
                    </li>
                    
                    <li class="list-item">
                        <div class="list-bullet" />
                        
                        Optional fillings: cheese, diced vegetables, cooked meats, herbs
                    </li>
                </ul>
            </div>

            <div class="line"></div>

            <div class="instruction">
                <h2 class="title-medium">
                    Instructions
                </h2>

                <ol class="list">
                    <li class="list-item list-item-ordered">
                        <div class="list-number">1.</div>
                        
                        <div>
                            <span class="list-item-subtitle">Beat the eggs:</span>
                            In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. 
                            You can add a tablespoon of water or milk for a fluffier texture.
                        </div>
                    </li>

                    <li class="list-item list-item-ordered">
                        <div class="list-number">2.</div>
                        
                        <div>
                            <span class="list-item-subtitle"> Heat the pan:</span>
                            Place a non-stick frying pan over medium heat and add butter or oil.
                        </div>
                    </li>
                    
                    <li class="list-item list-item-ordered">
                        <div class="list-number">3.</div>
                        
                        <div>
                            <span class="list-item-subtitle">Cook the omelette:</span>
                            Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure 
                            the eggs evenly coat the surface.
                        </div>
                    </li>
                    
                    <li class="list-item list-item-ordered">
                        <div class="list-number">4.</div>
                        
                        <div>
                            <span class="list-item-subtitle">Add fillings (optional):</span>
                            When the eggs begin to set at the edges but are still slightly runny in the 
                            middle, sprinkle your chosen fillings over one half of the omelette.
                        </div>
                    </li>
                    
                    <li class="list-item list-item-ordered">
                        <div class="list-number">5.</div>
                        
                        <div>
                            <span class="list-item-subtitle">Fold and serve:</span>
                            As the omelette continues to cook, carefully lift one edge and fold it over the 
                            fillings. Let it cook for another minute, then slide it onto a plate.
                        </div>
                    </li>
                    
                    <li class="list-item list-item-ordered">
                        <div class="list-number">6.</div>
                        
                        <div>
                            <span class="list-item-subtitle">Enjoy:</span>Serve hot, with additional salt and pepper if needed.
                        </div>
                    </li>
                </ol>
            </div>

            <div class="line"></div>

            <div class="nutrition">
                <h2 class="title-medium">
                    Nutrition
                </h2>

                <p class="nutrition-subtitle">
                    The table below shows nutritional values per serving without the additional fillings. 
                </p>

                <table class="nutrition-table">
                    <tr class="nutrition-table-row">
                        <td class="nutrition-table-cell">Calories</td>

                        <td class="nutrition-table-cell">277kcal</td>
                    </tr>

                    <tr class="nutrition-table-row">
                        <td class="nutrition-table-cell">Carbs</td>

                        <td class="nutrition-table-cell">0g</td>
                    </tr>

                    <tr class="nutrition-table-row">
                        <td class="nutrition-table-cell">Protein</td>

                        <td class="nutrition-table-cell">20g</td>
                    </tr>

                    <tr class="nutrition-table-row">
                        <td class="nutrition-table-cell">Fat</td>

                        <td class="nutrition-table-cell">22g</td>
                    </tr>
                </table>
            </div>
        </div>
    </main>
</template>

<style scoped>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    min-height: 100dvh;
    padding: 7.75rem 0;

    @media screen and (max-width: 640px) {
        padding: 0;
    }
}

.recipe {
    padding: 2.5rem;
    max-width: 46rem;
    background-color: var(--white);
    border-radius: 1.5rem;

    @media screen and (max-width: 640px) {
        padding: 2rem;
        border-radius: 0;
    }
}

.image {
    width: 100%;
    margin-bottom: 2.5rem;
    border-radius: 0.75rem;

    @media screen and (max-width: 640px){
        width: calc(100% + 4rem);
        margin-top: -2rem;
        margin-left: -2rem;
        border-radius: 0;
    }
}

.title {
    font-size: 2.5rem;
    font-family: 'YoungSerif', serif;
    font-weight: 700;
    color: var(--color-title);
    line-height: 100%;

    @media screen and (max-width: 640px) {
        font-size: 2.25rem;
    }
}

.title-medium {
    margin-bottom: 1.5rem;
    font-size: 1.75rem;
    line-height: 100%;
    font-family: 'YoungSerif', serif;
    color: var(--nutmeg);
}

.subtitle {
    margin-top: 1.5rem;
    line-height: 150%;
}

.preparation {
    margin: 2rem 0;
    padding: 1.75rem;
    background: var(--color-preparation-background);
    border-radius: 0.75rem;

    @media screen and (max-width: 640px) {
        padding: 1.5rem;
    }
}

.preparation-title {
    margin-bottom: 1rem;
    font-size: 1.25rem;
    line-height: 100%;
    color: var(--color-preparation-title);
}

.list {
    list-style: none;
    padding: 0;
}

.list-item {
    display: flex;
    align-items: center;
    margin-bottom: 0.5rem;
    line-height: 150%;
}

.list-item-ordered {
    align-items: start;
}

.list-item-subtitle {
    font-weight: 700;
}

.list-bullet {
    margin-left: 0.5rem;
    margin-right: 1.75rem;
    width: 0.25rem;
    height: 0.25rem;
    border-radius: 50%;
    background-color: var(--dark-raspberry);
}

.list-number {
    margin-left: 0.5rem;
    margin-right: 1.75rem;
    color: var(--dark-raspberry);
    font-weight: 700;
}

.ingredients {
    margin-top: 2rem;
}

.line {
    margin: 2rem 0;
    border: 1px solid var(--light-gray);
}

.nutrition-subtitle {
    margin: 1.5rem 0;
}

.nutrition-table {
    width: 100%;
    border-collapse: collapse;
}

.nutrition-table-cell {
    padding: 0.75rem 2rem;
}

.nutrition-table-cell:last-child {
    font-weight: 700;
    color: var(--dark-raspberry);
}

.nutrition-table-row:not(:last-child) {
    border-bottom: 1px solid var(--light-gray);
}
</style>
# Routing

In the browser, navigate to: http://localhost:3000

## Task One: Implement React Router for `Home`, `Signup`, `Login`, and `ProductsLayout`

1. `<main class="primary-content"></main>` Should always be present since it's meant to be the container for the pages.
2. Within it, create a `Switch` and several `Route`s for `Home`, `Signup`, `Login`, and `ProductsLayout`.
3. Use `Redirect` for when no `Routes` match in the `Switch`.

## Task Two: Conditional Routing for `Checkout`

4. Only create routing for `Checkout` if `cart.length` shows that we have items in the cart.

## Task Three: Conditional Routing for `Account`

5. Only create routing for `Account` if `authenticated` is `true`.

## Task Four: Conditional Routing for `ProductSubNav`

6. Only route to `ProductSubNav` if the path is `/products` (without the `exact` prop)
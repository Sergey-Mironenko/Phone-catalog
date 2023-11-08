# Online phone catalog

  A single-page application implements online store functionality. User can browse products, add them to the cart and favorites, search products, sort products, change the quantity of products per page and amount of pages, view product details.

# Technologies used

  - React.js
  - React Router
  - JSX
  - TypeScript
  - JavaScript
  - LoDash
  - Fetch, API
  - Sass (SCSS)
  - CSS Modules

# Structure

  App is built using functional components, React Hooks and Custom Hooks. Each component is abstract and fully reusable. Components are styled using Sass (SCSS). BEM methodology is used for naming and styling.

# Features & Functionality

  ## App:
  - Navigation is implemented using React Router.

  ## Header:
    - Search and filter products by name is implemented,
    - Debounce function is used in filtering to prevent the server from being overloaded with requests.

  ## Home page:
    - Main photo scrolls automatically every 5 seconds,
    - Products sliders with the ability to scroll products by clicking on the arrows.

  ## Catalog pages:
    - Products are fetched from the server by category,
    - Wait function was used to simulate the loading of products from the server to demonstrate the loader,
    - Ability to sort products by name, price, and age is implemented,
    - All sorting parameters are saved in the URL,
    - Pagination is implemented. The number of products displayed on the page can be changed by the user.

  ## Product details page:
    - Product details are fetched from the server,
    - Wait function was used to simulate the loading of products from the server to demonstrate the loader,
    - User can pick a color and capacity of the product,
    - Photos of the product can be changed by clicking on the thumbnails,
    - User can add the product to the cart or favorites.

  ## Favourites page:
    - User can add products to favorites and remove them from favorites,
    - Favorites count is shown near the Favorites icon in the header,
    - Favorites are saved in the local storage.

  ## Cart page:
    - User can change the quantity of products in the cart and remove products from the cart,
    - Cart items count is shown near the Cart icon in the header,
    - Total amount and quantity are calculated automatically,
    - Cart items are saved in the local storage.

# Reflections
 Project goals included using technologies learned up until this point and familiarizing myself with documentation for new features.

 I ran into necessity to use new features, such as:
   - loaders,
   - error boundaries,
   - data prefetching,
   - lazy loading,
   - new hooks (useCallback, useLocaleStorage etc.) I had to learn how to use them and implement them in the project,
   - Another challenge was to create custom useLocaleStorage hook, to save products to localeStorage and Context at the same time.

 When the project was finished, I've figured out how to work with bigger projects and how to use mentioned technologies all together.

# Demo link
 - https://sergey-mironenko.github.io/Phone-catalog/
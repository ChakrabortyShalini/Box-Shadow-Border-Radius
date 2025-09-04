### CSS Card Component with Box Shadow and Border Radius

This project demonstrates a simple, reusable card component built with HTML and CSS. It's a great starting point for creating elements like product cards, profile cards, or portfolio previews.

-----

### Features

  - **Clean and Modern Design**: The cards feature soft, rounded corners using `border-radius` and a subtle lift effect with `box-shadow`.
  - **Self-Contained**: All the necessary HTML and CSS are in a single file, making it easy to copy, paste, and run without any external dependencies.
  - **Easily Customizable**: You can quickly swap out images, text, and even colours to fit your project's needs.

-----

### How to Use

1.  **Copy the code**: Simply copy the HTML and CSS into a new file and save it as `index.html`.
2.  **Open in a browser**: Open the `index.html` file with any web browser to see the cards.

-----

### Customization

  - **Images**: To change the image on a card, replace the URL in the `src` attribute of the `<img>` tag.
  - **Content**: Modify the text within the `<h2>` and `<p>` tags to change the title and description.
  - **Layout**: For more advanced layouts, you can wrap multiple cards in a container `div` and use CSS Flexbox or Grid to arrange them. For example, to align them in a row:
    ```css
    .container {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
    }
    ```
  - **Styling**: Experiment with the `border-radius` and `box-shadow` values in the `.card` class to create different visual effects.

-----

### Example Use Cases

  - Product listings for an e-commerce site.
  - "Meet the Team" sections on a company website.
  - Project previews for a design portfolio.

-----

### License

This project is open source and available under the MIT License.

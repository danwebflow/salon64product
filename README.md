# Salon64 Shopify Theme

This is the custom Shopify theme for Salon64 Products.

## Development Setup

1. Install the Shopify CLI:
   ```bash
   npm install -g @shopify/cli
   ```

2. Authenticate with your store:
   ```bash
   shopify login --store salon64products.myshopify.com
   ```

3. Pull the latest theme:
   ```bash
   shopify theme pull --theme 137783214173 --store salon64products.myshopify.com
   ```

4. Start development server:
   ```bash
   shopify theme dev
   ```

## Theme Structure

- `assets/`: Contains all static assets (images, CSS, JavaScript)
- `config/`: Theme settings and configuration
- `layout/`: Theme layout templates
- `sections/`: Reusable theme sections
- `snippets/`: Reusable code snippets
- `templates/`: Page templates

## Development Workflow

1. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes to the theme files

3. Test your changes locally using the development server

4. Commit your changes:
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

5. Push your changes to GitHub:
   ```bash
   git push origin feature/your-feature-name
   ```

6. Create a Pull Request on GitHub

7. After review and approval, merge your changes to main

8. Deploy your changes to the live theme:
   ```bash
   shopify theme push --theme 137783214173 --store salon64products.myshopify.com
   ```

## Theme Features

- Custom product pages
- Range selection functionality
- Ingredients and benefits sections
- Sign-up and thank you pages
- Responsive design

## Best Practices

1. Always test changes locally before pushing to production
2. Use meaningful commit messages
3. Keep the theme organized and maintainable
4. Follow Shopify's theme development guidelines
5. Regularly backup your theme files

## Troubleshooting

If you encounter issues:
1. Check the Shopify CLI documentation
2. Verify your authentication status
3. Ensure you have the correct theme ID
4. Check for any merge conflicts
5. Clear your browser cache when testing changes 
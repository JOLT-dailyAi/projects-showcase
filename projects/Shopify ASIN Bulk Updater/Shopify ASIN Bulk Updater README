# Shopify ASIN Bulk Updater - Proof of Concept

**Live Demo:** [https://jolt-dailyai.github.io/projects-showcase/projects/Shopify%20ASIN%20Bulk%20Updater/shopify-asin-updater.html](https://jolt-dailyai.github.io/projects-showcase/projects/Shopify%20ASIN%20Bulk%20Updater/shopify-asin-updater.html)

## What This Tool Does

Automatically copies SKU values to `amazon.asin` metafields for Shopify products where the SKU matches Amazon ASIN format (10 characters starting with 'B'). This enables seamless affiliate link management for stores selling Amazon products.

## Important Limitation

**This is a proof-of-concept tool that requires technical setup.** Each store owner must:
1. Create their own private Shopify app
2. Generate an Admin API access token with product read/write permissions
3. Manually enter their credentials

This approach limits usability to technical users or situations where setup assistance is provided.

## Development Path Forward

This prototype serves as the foundation for a full Shopify App Store application that would:
- Handle OAuth authentication automatically
- Eliminate manual token setup
- Provide better error handling and user management
- Be accessible to any Shopify store owner without technical knowledge

The core functionality, UI design, and user experience demonstrated here would transfer directly to a production app built using Shopify's app development framework.

## Technical Features

- **GraphQL API Integration:** Uses Shopify's Admin GraphQL API for efficient bulk operations
- **Real-time Progress Tracking:** Visual progress bars and detailed logging
- **Batch Processing:** Configurable batch sizes with rate limiting
- **ASIN Validation:** Checks SKU format before processing
- **Error Handling:** Comprehensive error reporting and status updates
- **Responsive Design:** Works on desktop and mobile devices

## Setup Requirements

1. **Shopify Store** with admin access
2. **Private App Creation:**
   - Go to Settings → Apps and sales channels → Develop apps
   - Create new app with product read/write permissions
   - Generate Admin API access token
3. **Store Configuration:**
   - Store name (without .myshopify.com)
   - Admin API access token
   - Products with SKUs containing valid ASINs

## Usage Flow

1. **Test Connection:** Verify API credentials work
2. **Preview Updates:** Scan products and show eligible items
3. **Bulk Update:** Process all eligible products with progress tracking
4. **Monitor Results:** Real-time logging and statistics

## Technology Stack

- **Frontend:** HTML5, CSS3 (CSS Custom Properties), Vanilla JavaScript
- **API:** Shopify Admin GraphQL API
- **Features:** ES6+ async/await, fetch API, DOM manipulation
- **Design:** Instagram-inspired dark theme with modern UI patterns

## File Structure

```
Shopify ASIN Bulk Updater/
├── shopify-asin-updater.html    # Complete application
└── README.md                    # This documentation
```

## Future Development

This proof of concept demonstrates the viability of the core functionality. A production version would be built as a proper Shopify app using:
- Shopify CLI and app templates
- OAuth for seamless authentication  
- Backend API for secure token handling
- App Store distribution for easy installation

The existing code provides a solid foundation for this evolution, with most logic and UI components directly transferable to the production framework.

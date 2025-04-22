# Heyland

Heyland is a Telegram bot able to create landing pages in seconds. These landing pages are intended as destinations for Meta and Google Ads campaigns where the visitors fill a form. 

## Features
- **✅ Facebook Tracking**: Supports Pixel and **Conversion API** for Meta event tracking.
- **✅ Google Ads Tracking**: Integrates Google Tag for seamless conversion tracking.
- **✅ Translations**: Translate content, prices, names and locations for different languages and regions. Example: if you are translating for Mexico, it will automatically put mexican names, mexican cities and mexican currency.
- **✅ Webhook Integration**: You can provide your webhook URLs (for example generated with Make.com) where you track your leads.
- **✅ Mobile-Optimized**: Fast page loads on mobile, outperforms WordPress+Elementor in drop-off rates.
- **✅ AI Copywriting**: It can generate copy using ChatGPT based on your product description.
- **✅ Templates**: Choose from available templates (currently Template 1) with preview functionality.
- **✅ Image Processing**: Upload up to 11 images. If you upload less the last one is replicated in the other locations.
- **✅ Instant Deployment**: the landing pages that you generated are available in 10 seconds after the bot sends you the link.

## Upcoming Features
- **Adult Content Translation**: Translations for adult/explicit content. This uses unrestricted LLMs and the APIs usege is pricy.
- **New Templates**
- **Password-Protected Templates**: Custom, exclusive templates with private access. if you have a winning template that you only want to use, and not accessible to others, you can have it password protected.
- **Custom Domain**: decide your own domain, not only your slug. 
- **Heatmap Analytics**: Visualize user interactions to optimize page performance.
- **TikTok Tracking**: TikTok Pixel integration for ad campaign tracking.
- **Generate Google Sheet**: if you don't want to provide a webhook, it automatically generates a google spreadsheet where you can track all your leads. 
- **Integration with Worldfilia**: no need to set up the webhook on Make.com anymore, just send the link of the Worldfilia product to the bot and it will do it for you.

## How to use
- Send `/start` in Telegram to begin. `/cancel` to stop your current flow.
- You want to use Facebook Conversion APIs? You just need you Pixel number and your Access Token.
- Where to find your Facebook Access Token? Go to the Events Manager in your Facebook Business Manager, select Data Source, select the pixel you want, go to the Settings tab, scroll down to the Conversion API section, and click "Generate access token"

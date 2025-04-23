# Heyland

Heyland is a Telegram bot able to create landing pages in seconds. These landing pages are intended as destinations for Meta and Google Ads campaigns where the visitors fill a form. 

## Features
- **✅ Facebook Tracking**: Supports Pixel and **Conversion API** for Meta event tracking.
- **✅ Google Ads Tracking**
- **✅ Translations**: Translate content, prices, names and locations for all languages and regions. Example: if you are translating for Mexico, it will automatically put mexican names, mexican cities and mexican currency; and of course all the content of the page translated in mexican-spanish.
- **✅ Webhook Integration**: You can provide your webhook URLs (for example generated with Make.com) where you track your leads.
- **✅ Mobile-Optimized**: Fast loads on mobile, outperforms WordPress+Elementor in drop-off rates.
- **✅ AI Copywriting**: It can generate copy using ChatGPT APIs based on your product description. **Please don't ask the AI to generate adult/explicit content yet**. This funcionality is upcoming but right now the text generation is made by ChatGPT which is restricted and checks for policy violations requests.
- **✅ Image Processing**: Upload up to 11 images. If you upload less, the last one is replicated in the other positions.
- **✅ Instant Deployment**: the landing pages are online in 10 seconds after the bot sends you the link.

## Upcoming Features
- **Adult Content Translation**: Translations for adult/explicit content. This uses unrestricted LLMs and the APIs usege is pricy.
- **New Templates**
- **Password-Protected Templates**: Custom templates with private access. If you have a template that you only want to be able touse, not accessible to others, you can have it password protected.
- **Custom Domain**: decide your own domain, not only your slug. 
- **Heatmap Analytics**: Visualize user interactions to optimize page performance.
- **TikTok Tracking**: TikTok Pixel integration for ad campaign tracking.
- **Generate Google Sheet**: if you don't want to provide a webhook, it automatically generates a google spreadsheet where you can track all your leads. 
- **Integration with Worldfilia**: no need to set up the automation on Make.com anymore, just send the link of the Worldfilia product to the bot and it will do it for you.

## How to use
- Send `/start` in Telegram to begin. `/cancel` to stop your current flow.
- You want to use Facebook Conversion APIs? You just need you Pixel number and your Access Token.
- Where to find your Facebook Access Token? Go to the Events Manager in your Facebook Business Manager, select Data Source, select the pixel you want, go to the Settings tab, scroll down to the Conversion API section, and click "Generate access token"

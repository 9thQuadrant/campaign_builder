# Campaign URL Builder 🚀

[![Netlify Status](https://api.netlify.com/api/v1/badges/b2c4ed18-30b2-46e9-9314-9f0d0e33cf89/deploy-status)](https://app.netlify.com/projects/custom-campaign-builder/deploys)

A free, open-source, single-page **Campaign URL Builder** tool for creating custom marketing campaign URLs with dynamic UTM parameters and query strings. Built with pure vanilla JavaScript - no frameworks, no dependencies!

## 🎯 What is a Campaign URL Builder?

A Campaign URL Builder is a tool that helps marketers, advertisers, and web analysts create trackable URLs with custom query parameters (UTM parameters) to measure the effectiveness of marketing campaigns across different channels.

## ✨ Features

- ✅ **100% Free & Open Source** - No API keys, no subscriptions, no limitations
- ✅ **Single HTML File** - Everything in one file, works offline
- ✅ **Zero Dependencies** - Pure vanilla JavaScript, no frameworks needed
- ✅ **Dynamic Query Parameters** - Add unlimited custom parameters
- ✅ **Live URL Preview** - See your URL being built in real-time
- ✅ **UTM Parameter Support** - Perfect for Google Analytics tracking
- ✅ **URL Encoding** - Automatically encodes special characters
- ✅ **Referrer Tracking** - Sets document.referrer when redirecting
- ✅ **Modern UI** - Beautiful, responsive design with smooth animations
- ✅ **Mobile Friendly** - Works perfectly on all devices
- ✅ **No Installation Required** - Just open and use

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
**🌐 Live Demo: [https://custom-campaign-builder.netlify.app/](https://custom-campaign-builder.netlify.app/)**

No installation needed! Access the tool instantly in your browser.

### Option 2: Direct Use
1. Download `campaign-builder.html`
2. Open it in any web browser
3. Start building campaign URLs!

### Option 2: Host It Yourself
```bash
# Serve locally with Python
python3 -m http.server 8000

# Or with Node.js
npx serve

# Then open http://localhost:8000/campaign-builder.html
```

## 📖 How to Use

### Basic Usage

1. **Enter Your Website URL**
   ```
   https://example.com
   ```

2. **Add Query Parameters** (click "+ Add Parameter" button)
   - Parameter name: `utm_source`
   - Value: `google`

3. **Add More Parameters** (optional)
   - `utm_medium` → `cpc`
   - `utm_campaign` → `spring_sale`
   - `utm_content` → `banner_ad`
   - `utm_term` → `running_shoes`

4. **Preview Your URL**
   ```
   https://example.com?utm_source=google&utm_medium=cpc&utm_campaign=spring_sale
   ```

5. **Click "Generate & Go to URL"** - Redirects to your custom URL

### Common Use Cases

#### Google Ads Campaign Tracking
```
Base URL: https://yourwebsite.com/product
utm_source: google
utm_medium: cpc
utm_campaign: summer_2025
utm_content: text_ad_v1
utm_term: buy_shoes_online
```

#### Facebook Ad Campaign
```
Base URL: https://yourwebsite.com/landing
utm_source: facebook
utm_medium: social
utm_campaign: product_launch
utm_content: carousel_ad
```

#### Email Newsletter
```
Base URL: https://yourwebsite.com
utm_source: newsletter
utm_medium: email
utm_campaign: weekly_digest
utm_content: header_cta
```

#### Custom Tracking Parameters
```
Base URL: https://yourwebsite.com
campaign_id: 12345
referral_code: FRIEND20
tracking_id: abc123
```

## 🎓 Understanding UTM Parameters

UTM parameters are tags added to URLs to track marketing campaign performance in analytics tools like Google Analytics.

| Parameter | Description | Example |
|-----------|-------------|---------|
| `utm_source` | Identifies the traffic source | `google`, `facebook`, `newsletter` |
| `utm_medium` | Identifies the marketing medium | `cpc`, `email`, `social`, `banner` |
| `utm_campaign` | Identifies the specific campaign | `spring_sale`, `product_launch` |
| `utm_content` | Differentiates similar content | `logolink`, `textlink`, `banner_ad` |
| `utm_term` | Identifies paid search keywords | `running_shoes`, `buy_laptop` |

## 🔧 Technical Details

### Technology Stack
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations and gradients
- **Vanilla JavaScript (ES6+)** - No frameworks or libraries
- **Class-based Architecture** - Clean, maintainable code

### Browser Support
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Features Breakdown

#### URL Encoding
Automatically encodes special characters to ensure valid URLs:
```javascript
encodeURIComponent(key) + '=' + encodeURIComponent(value)
```

#### Dynamic Parameter Management
- Add unlimited parameters dynamically
- Remove parameters with smooth animations
- Real-time URL preview updates

#### Referrer Tracking
When you submit the form, it redirects to the constructed URL using `window.location.href`, which properly sets the `document.referrer` for the target website.

## 🎨 Customization

The tool is easy to customize! Edit the HTML file to:

- Change colors and styling (CSS section)
- Modify default parameters
- Add pre-filled common templates
- Customize button text and labels
- Add additional validation rules

## 🔍 SEO & Marketing Keywords

This tool is perfect for:
- UTM builder
- Campaign URL generator
- Google Analytics URL builder
- Marketing link builder
- URL parameter builder
- Tracking link creator
- Google Ads URL builder
- Facebook Ads link builder
- Email marketing URL tracker
- Social media link tracker
- Referrer tracking tool
- Query string builder
- Custom URL parameters
- Link tracking tool
- Marketing attribution tracker

## 💡 Use Cases

### Digital Marketing
- Track Google Ads campaigns
- Monitor Facebook/Instagram ads
- Measure email newsletter effectiveness
- Analyze social media traffic
- Compare different ad creatives

### E-commerce
- Track product launches
- Monitor discount campaigns
- Analyze affiliate links
- Measure influencer marketing ROI

### Content Marketing
- Track blog post promotions
- Monitor guest post traffic
- Analyze newsletter CTR
- Measure content distribution

### Analytics & Reporting
- Create clean, organized traffic reports
- Segment traffic by channel
- Compare campaign performance
- Track conversion sources

## 🔒 Privacy & Security

- ✅ **100% Client-Side** - No data sent to servers
- ✅ **No Tracking** - We don't track your usage
- ✅ **No Cookies** - No data stored
- ✅ **Offline Capable** - Works without internet
- ✅ **Open Source** - Full code transparency

## 📱 Screenshots & Demo

The tool features:
- Clean, modern interface with black background
- Smooth fade-in animations
- Slide-in effects for new parameters
- Slide-out animations when removing parameters
- Live URL preview panel
- Responsive mobile design

## 🤝 Contributing

This is an open-source tool! Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Fork and customize for your needs

## 📄 License

This project is open source and available under the MIT License. Free to use for personal and commercial projects.

## 🌟 Related Tools

- Google's Campaign URL Builder
- Bitly Campaign Builder
- UTM.io
- Campaign URL Builder Chrome Extensions

## 📞 Support & Resources

### Google Analytics Documentation
- [About Campaign URL Builder](https://support.google.com/analytics/answer/1033867)
- [UTM Parameters Guide](https://support.google.com/analytics/answer/1033863)

### Marketing Resources
- Learn about campaign tracking best practices
- Understand marketing attribution
- Master Google Analytics tracking

## 🚀 Future Enhancements

Potential features for future versions:
- [ ] Save/load campaign templates
- [ ] URL shortening integration
- [ ] QR code generation
- [ ] Bulk URL generation
- [ ] CSV export functionality
- [ ] Dark mode toggle
- [ ] Parameter validation rules
- [ ] Preset templates library

## 📊 Why Use This Tool?

1. **Free Forever** - No hidden costs or premium features
2. **Privacy First** - Your data stays on your device
3. **Fast & Lightweight** - Single HTML file, loads instantly
4. **Easy to Use** - Intuitive interface, no learning curve
5. **Professional Results** - Generate properly formatted URLs
6. **Reliable** - No external dependencies, always works
7. **Customizable** - Open source, modify as needed

## 🎯 Perfect For

- Digital Marketers
- Marketing Agencies
- E-commerce Businesses
- Social Media Managers
- Email Marketers
- Content Creators
- Web Analysts
- SEO Specialists
- PPC Specialists
- Affiliate Marketers

---

**Made with ❤️ using Vanilla JavaScript**

*No frameworks were harmed in the making of this tool*

Keywords: campaign url builder, utm builder, google analytics url builder, marketing url generator, tracking link creator, utm parameter generator, free campaign builder, url parameter builder, marketing link builder, google ads url builder, facebook ads link builder, referrer tracking, query string builder, vanilla javascript, single page application, open source marketing tool


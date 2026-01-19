# Blogtagg - Blogshop Search Engine

Cloud-based search engine and tagging service for Singapore blogshops (online fashion stores). Aggregates RSS feeds from multiple blogshops and provides fast, tag-based search to help users find fashion items across hundreds of independent online stores.

Launched in 2011 as "Stop searching, start finding" - a centralized discovery platform for Singapore's fragmented blogshop ecosystem.

## Features

- RSS feed aggregation from Singapore blogshops
- Tag-based product search and filtering
- Centralized blogshop directory
- Real-time product indexing
- Google Analytics integration
- Facebook social integration
- SEO-optimized product listings

## Tech Stack

- **Platform**: Windows Azure Cloud Services (now Azure App Service)
- **Backend**: ASP.NET Web Forms, C#
- **Framework**: .NET Framework
- **Hosting**: Azure WebRole
- **Analytics**: Google Analytics
- **Social**: Facebook Like Box integration

## Architecture

- **WebRole1**: ASP.NET web application hosted on Azure Cloud Services
- **RSS Aggregation**: Automated feed crawling and parsing
- **Tagging Engine**: Product categorization and tag extraction
- **Search Index**: Fast lookup for product discovery
- **SEO Optimization**: Canonical URLs, meta descriptions, sitemap

## Use Case

In 2011, Singapore had hundreds of independent fashion blogshops, each posting products on their own blogs. Finding specific items (e.g., "floral dress") required manually visiting dozens of blogs. Blogtagg solved this by:

1. Automatically crawling blogshop RSS feeds
2. Extracting product posts and images
3. Tagging products by category, color, style
4. Providing centralized search interface
5. Linking back to original blogshops for purchase

## Installation

1. Open `CloudService.sln` in Visual Studio
2. Restore NuGet packages
3. Configure Azure Cloud Service connection
4. Update database connection strings in Web.config
5. Deploy to Azure or run locally with Azure Emulator

## Configuration

```xml
<!-- Web.config -->
<connectionStrings>
  <add name="BlogtaggDB" connectionString="..." />
</connectionStrings>
```

## License

MIT License

## Links

- Blog post: [www.tanchunsiong.com](https://www.tanchunsiong.com)
- GitHub: [github.com/tanchunsiong](https://github.com/tanchunsiong)
- LinkedIn: [linkedin.com/in/tanchunsiong](https://linkedin.com/in/tanchunsiong)
- X: [x.com/tanchunsiong](https://x.com/tanchunsiong)

**Project Created:** 2011

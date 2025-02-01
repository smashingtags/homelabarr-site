# HomelabARR Landing Page

The official landing page for HomelabARR - A comprehensive Docker-based application for managing and monitoring your homelab container applications.

![Interface Preview](https://github.com/smashingtags/homelabarr-assets/blob/main/screenshots/homelabarr-website.png?raw=true)

🔗 **[Live Demo](https://homelabarr.com)**

## 🚀 Features

- **Modern Design**: Built with Astro for optimal performance and SEO
- **Interactive Gallery**: Showcase application screenshots with PhotoSwipe integration
- **Real-time Stats**: Display GitHub stars and Discord member counts
- **Responsive Layout**: Fully responsive design that works on all devices
- **Docker Ready**: Easy deployment with Docker and nginx

## 🛠️ Tech Stack

- [Astro](https://astro.build) - Static Site Generator
- [TypeScript](https://www.typescriptlang.org/) - Type Safety
- [PhotoSwipe](https://photoswipe.com/) - Image Gallery
- [Docker](https://www.docker.com/) - Containerization
- [Nginx](https://nginx.org/) - Web Server

## 🏃‍♂️ Quick Start
```bash
   git clone https://github.com/smashingtags/homelabarr-site.git
   cd homelabarr-site
   docker compose -f homelabarr-site.yml up -d
   ```
The app will be available on http://localhost:8087

## 🏃‍♂️ Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/smashingtags/homelabarr-site.git
   cd homelabarr-site
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:4321](http://localhost:4321) in your browser

## 🐳 Docker Deployment

### Using Docker Compose (Recommended)

1. Clone the repository
2. Run with docker-compose:
   ```bash
   docker-compose up -d
   ```

### Manual Docker Build

1. Build the image:
   ```bash
   npm run docker:build
   ```

2. Run the container:
   ```bash
   npm run docker:run
   ```

## 📦 Project Structure

```
/
├── public/          # Static assets
├── src/
│   ├── components/  # UI components
│   ├── layouts/     # Page layouts
│   └── pages/       # Page components
├── Dockerfile       # Docker configuration
└── nginx.conf       # Nginx configuration
```

## 🔧 Configuration

### Environment Variables

No environment variables are required for basic setup. The site is completely static.

### Nginx Configuration

The default nginx configuration in `nginx.conf` includes:
- Gzip compression
- Cache control headers
- CORS headers
- Static asset optimization

## 📝 License

[MIT License](LICENSE)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

- [Discord Server](https://discord.gg/Pc7mXX786x)
- [Demo Site](https://homelabarr.com)
- [GitHub Issues](https://github.com/smashingtags/homelabarr-site/issues)

## 🌟 Related Projects

- [HomelabARR Main Repository](https://github.com/smashingtags/homelabarr)
- [HomelabARR Frontend](https://hub.docker.com/repository/docker/smashingtags/homelabarr-frontend)
- [HomelabARR Backend](https://hub.docker.com/repository/docker/smashingtags/homelabarr-backend)

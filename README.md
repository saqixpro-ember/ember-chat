# Ember Chat

Ember Chat is an organized team chat application with topic-based threading that combines the best of email and chat to make remote work productive and delightful.

Built on the proven Zulip open-source platform and customized with Ember branding, Ember Chat provides a modern team chat experience designed for both live and asynchronous conversations.

## About This Project

Ember Chat is a customized fork of [Zulip](https://github.com/zulip/zulip), an open-source team chat application. We've rebranded and customized it to meet our specific needs while maintaining the powerful features that make Zulip great.

### Key Features

- **Topic-based threading** - Organize conversations by topic for clarity
- **Powerful search** - Find any message quickly
- **Rich formatting** - Markdown support, code syntax highlighting
- **Mobile apps** - Native iOS and Android applications
- **Integrations** - Connect with your favorite tools
- **Self-hosted** - Full control over your data

## Getting Started

### Prerequisites

- Ubuntu 22.04 or Debian 11/12
- At least 2GB RAM
- Python 3.8+
- PostgreSQL 14+

### Quick Installation

For detailed installation instructions, see the [Zulip installation documentation](https://zulip.readthedocs.io/en/latest/production/install.html).

```bash
# Download and run the installer
cd /root
wget https://download.zulip.com/server/zulip-server-latest.tar.gz
tar -xf zulip-server-latest.tar.gz
./zulip-server-*/scripts/setup/install
```

### Development Setup

```bash
# Clone the repository
git clone https://github.com/your-org/ember-chat.git
cd ember-chat

# Run the development environment
./tools/provision
./tools/run-dev
```

## Documentation

This project is based on Zulip. For comprehensive documentation, refer to:

- [Zulip Documentation](https://zulip.readthedocs.io/)
- [Zulip API Documentation](https://zulip.com/api/)
- [Zulip Help Center](https://zulip.com/help/)

## Technology Stack

- **Backend**: Python/Django
- **Frontend**: TypeScript, jQuery
- **Database**: PostgreSQL
- **Cache**: Redis/Memcached
- **Search**: Custom full-text search

## License

Ember Chat is based on Zulip, which is licensed under the Apache License 2.0.

```
Copyright 2012–2015 Dropbox, Inc., 2015–2021 Kandra Labs, Inc., and contributors

Modified 2026 as Ember Chat

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

See the [LICENSE](LICENSE) file for the full license text.

## Acknowledgments

This project is built on the excellent work of the Zulip team and community. We're grateful for their contributions to open-source software.

Original Zulip project: https://github.com/zulip/zulip

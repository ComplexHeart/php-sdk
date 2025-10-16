# Complex Heart PHP SDK

[![Test](https://github.com/ComplexHeart/php-sdk/actions/workflows/test.yml/badge.svg)](https://github.com/ComplexHeart/php-sdk/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![PHP Version](https://img.shields.io/badge/php-%5E8.2-blue)](https://www.php.net/)

An SDK for building Domain-Driven Design (DDD) applications in PHP. This metapackage bundles the essential Complex Heart libraries to provide a complete toolset for implementing DDD patterns with value objects, entities, aggregates, and flexible query criteria.

## Overview

The Complex Heart SDK is designed to ease the adoption of Domain-Driven Design principles in PHP projects by providing well-tested, production-ready components that handle common DDD patterns and challenges.

## Features

This SDK includes three core packages:

- **[Contracts](https://github.com/ComplexHeart/php-contracts)** - Common interfaces and contracts to decouple domain logic from infrastructure concerns
- **[Domain Model](https://github.com/ComplexHeart/php-domain-model)** - Base classes and utilities for building Aggregates, Entities, and Value Objects
- **[Criteria](https://github.com/ComplexHeart/php-criteria)** - Flexible query pattern implementation for building type-safe, repository-agnostic queries

## Requirements

- PHP ^8.2
- ext-json

## Installation

Install via Composer:

```bash
composer require complex-heart/sdk
```

This will install all three packages and their dependencies.

## What's Included

### Contracts Package
Provides foundational interfaces for:
- Value Objects
- Entities and Aggregates
- Domain Events
- Repositories
- Services

### Domain Model Package
Offers base implementations for:
- Value Objects with validation and immutability
- Entities with identity management
- Aggregate roots with domain event handling
- Rich domain behaviors

### Criteria Package
Enables flexible querying with:
- Type-safe query building
- Filtering, ordering, and pagination
- Repository-agnostic design
- Composable query specifications

## Documentation

For detailed documentation on each package, please visit:

- [Contracts Documentation](https://github.com/ComplexHeart/php-contracts#readme)
- [Domain Model Documentation](https://github.com/ComplexHeart/php-domain-model#readme)
- [Criteria Documentation](https://github.com/ComplexHeart/php-criteria#readme)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## Support

If you encounter any issues or have questions:

- Open an issue on [GitHub Issues](https://github.com/ComplexHeart/php-sdk/issues)
- Check existing issues and discussions
- Review the documentation for each individual package

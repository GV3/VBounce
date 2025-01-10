# VBounce Trading Strategy

A TradingView Pine Script strategy that implements an advanced bounce trading system with trailing stops and webhook integration.

## Features

- **Smart Entry System**:
  - Detects price drops from peak levels
  - Uses trailing stop entry to catch the bounce
  - Configurable minimum drop percentage
  
- **Advanced Exit Management**:
  - Take profit targets
  - Stop loss protection
  - Dynamic trailing stop that activates at specified profit levels
  
- **Risk Management**:
  - Position sizing based on account equity
  - Percentage-based stops and targets
  - Trailing stop protection

## Technical Details

- Written in Pine Script v5
- Implements mock trailing stop functionality
- Includes webhook integration for external order execution
- Comprehensive plotting and status display

## Version

Current Version: 3.1.3

## Requirements

- TradingView Pro account
- Webhook integration setup for order execution
- External order execution system compatible with the webhook format

## License

All rights reserved. This source code is protected and cannot be used without explicit permission.

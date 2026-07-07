# v1.1.1
## 07/06/2026

1. [](#bugfix)
   * Removed a redundant check that blocked webhook and health endpoints unless a `scheduler.modern.enabled` setting was on, a toggle that no longer exists in Grav 2.

# v1.1.0
## 05/06/2026

1. [](#new)
   * Added Grav 2.0 compatibility 

# v1.0.1
## 04/30/2026

1. [](#bugfix)
    * Fixed PHP 8.1+ deprecation notice — explicit string casts where `null` was being passed to string-typed function arguments.

# v1.0.0
## 08/25/2025

1. [](#new)
    * Initial release of Scheduler Webhook plugin
    * Webhook endpoint for triggering scheduler
    * Health check endpoint for monitoring
    * Bearer token authentication
    * Support for triggering specific jobs
    * Optional CORS support
    * Comprehensive documentation and examples
# Authentication Flow

1. User logs into main application
2. Backend issues JWT token
3. Token is used across:
   - dashboard
   - public site
4. Backend validates token per request
5. Role-based permissions applied per tenant

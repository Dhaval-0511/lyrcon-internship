# Lyrcon Solutions Internship

## Software Developer Internship

**Company:** Lyrcon Solutions  
**Duration:** 1 month  
**Project:** [AutoNidhi](https://github.com/dhruvil-1207/auto-nidhi)

This repository summarizes my contributions during my second internship at Lyrcon Solutions. AutoNidhi is a collaborative finance operations platform for vehicle-loan companies, built with React, TypeScript, FastAPI, PostgreSQL, and machine-learning services.

## My Contributions

### Frontend and Responsive Experience

- Reworked the homepage into a responsive, mobile-first layout.
- Added responsive behavior across admin, customer, accountant, and data-entry portals.
- Added mobile sidebar drawers, navigation controls, overlays, responsive dashboard grids, mobile-friendly filters, horizontal table scrolling, and bottom-sheet style dialogs.
- Improved feature-card layouts and typography across smaller screen sizes.

### Product Features and Role Workflows

- Implemented staff allocation and customer-portal updates.
- Replaced five staff payment and expense page stubs with working components connected to the existing admin implementations.
- Added role-appropriate access behavior so staff pages inherit real data, pagination, search, and export functionality while restricting admin-only actions.
- Added bank-account fields and an edit-details workflow for user administration.

### API Integration and Reliability

- Fixed API paths for staff and accountant modification workflows.
- Fixed the admin review-desk pipeline and evaluation endpoints.
- Removed an unnecessary local-storage dependency from customer service-request submissions; the backend now identifies customers through the authenticated session.
- Prevented the authentication interceptor from redirecting public pages to the login screen.

### Data and Machine-Learning Support

- Added a re-runnable real-world seed-data migration using the database URL from the environment.
- Implemented a Random Forest training and evaluation pipeline.
- Updated ML feature preprocessing and target encoding.

## Technologies

React 19 · TypeScript · Vite · Ant Design · Recharts · FastAPI · PostgreSQL · SQLAlchemy · Python · XGBoost · LightGBM · CatBoost · scikit-learn

## Collaboration

AutoNidhi was developed collaboratively. My work was delivered through feature branches and pull requests in the original repository. The linked project is the source of truth for the complete application and team contributions.

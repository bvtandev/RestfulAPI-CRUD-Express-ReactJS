## What learn?

#### 1. Setup

- install nodejs
- npx create-react-app .
- npm i axios react-router-dom react-toastify
- install extensions:
  - ES7+ React/Redux/React-Native snippets
  - Material Icon Theme
  - Material Theme
- install chrome extensions:
  - React Developer Tools
  - Redux DevTools
  - JSONVue
- Declare axios, react-router-dom, react-toastify
- Import fonts

#### 2. Create Home Page

- Router configuration.
- Create Components
  - Products
  - ProductsCard
- Use props, state and useEffect.

#### 3. Create ProductDetail Page

- Router configuration.
- Create Components
  - ProductInfo
- Custom hooks (useQuery).
- Caching Data

#### 4. Pagination

- Create Components
  - Pagination(limit, totalPages, currentPage)
- Use React.memo and useMemo
- Custom hooks (usePagination)

#### 5. Sorting

- Create Components and import in Home.js
  - Sorting
- Use React Context
- Custom hooks (useCustomRouter)

#### 6. Create Header, Search and Filtering

- Router configuration.
- Create Components
  - Header
  - Modal
  - SearchForm
  - FilterForm
- Create Pages
  - Search
  - Filter

#### 7. Create, Update and Delete Product

- Create Components
  - ProductForm
- Import Components in Header
- Import Components in ProductCard
- Use React Context
- Custom hooks (useMutation)

#### 8. Infinity Loading and Sort

- Search
- Filter
- Custom hooks (useInfinityQuery)

#### 9. useReducers

- Update useMuatation

## Getting started Demo:

```
Add your mongodb_url in api/.env and run:
Docker: `docker-compose up`
Without Docker:
Client: `cd client -> npm install -> npm start`
API: `cd api -> npm install -> npm run dev`

```

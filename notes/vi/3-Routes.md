# Routes & Route

## Routes

Có thể đặt ở bất kỳ vị trí nào trang app
Hỗ trợ tìm kiếm route đúng nhất với URL trên addressbar và render ra UI.

```jsx
import { BrowserRouter, Routes } from 'react-router-dom';

<BrowserRouter>
  <Routes>
    <App />
  </Routes>
</BrowserRouter>;
```

## Route

Định nghĩa element phù hợp với route dựa trên addressbar URL

```jsx
import { BrowserRouter, Routes, Route } from 'react-router-dom';

<BrowserRouter>
  <Routes>
    <Route path="/" element={<Dashboard />} />
    <App />
  </Routes>
</BrowserRouter>;
```

# React Router Setup & BrowserRouter

## BrowserRouter (NO data APIs)

Tương đương context của react router dùng để wrap app lại để sử dụng component & hooks có sẫn trong react router dom.

Lưu trữ vị trí hiện tại của addressbar trên trình duyêt qua URL và chuyển hướng thông qua built-in history stack của trình duyệt.

```jsx
import { BrowserRouter } from 'react-router-dom';

createRoot(document.getElementById('root')!).render(
  <StrictMode>
    <BrowserRouter>
      <App />
    </BrowserRouter>
  </StrictMode>
);
```

## createBrowserRouter (nên dùng, hỗ trơ data APIs)

Dùng [DOM History API](https://developer.mozilla.org/en-US/docs/Web/API/History) của trình duyêt để cập nhật và quản lý history stack.

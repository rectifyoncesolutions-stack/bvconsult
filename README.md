```
│  ├─ _app.js
        @keyframes float {
          0% { transform: translateY(0px); }
          50% { transform: translateY(-12px); }
          100% { transform: translateY(0px); }
        }
      `}</style>
    </div>
  )
}
```

---

## styles/globals.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

html, body, #__next { height: 100%; }

/* small helper styles used by components */
.perspective-1000 { perspective: 1000px; }
.cube { transform-style: preserve-3d; }
.face { backface-visibility: hidden; }
```

---

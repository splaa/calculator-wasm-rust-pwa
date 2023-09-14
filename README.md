```bash
cargo new calculator-wasm-rust-pwa --bin
```


```bash
cargo add eframe --no-default-features -F default_fonts -F glow -F persistence
```

> - `default_fonts` - Позволяет добавить в проект шрифты `egui` по умолчанию.
> - `glow` - Указываем `egui`, что необходимо использовать `glow` как бэкэнд рендеринга. Альтернатива: "wgpu".
>- `persistence` - Позволит нам реализовать восстановление состояние приложения при перезапуске приложения.



https://doc.rust-lang.org/cargo/reference/manifest.html
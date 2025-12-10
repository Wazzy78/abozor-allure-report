# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - alert [ref=e2]
  - generic [ref=e3]:
    - banner [ref=e5]:
      - generic [ref=e7]:
        - link "main-logo" [ref=e8] [cursor=pointer]:
          - /url: /
          - img "main-logo" [ref=e9]
        - generic [ref=e10]:
          - textbox [ref=e13] [cursor=pointer]: O'z
          - button [ref=e14] [cursor=pointer]
    - generic [ref=e20]:
      - generic [ref=e21]:
        - paragraph [ref=e24]: Abozor Diagnostika
        - generic [ref=e25]:
          - paragraph [ref=e26]: Diagnostikaga ro'yxatdan o'tish uchun ma'lumot qoldiring
          - generic [ref=e27]:
            - generic [ref=e28]: Ism
            - textbox "Ism" [ref=e30]:
              - /placeholder: Ismingizni kiriting
          - generic [ref=e31]:
            - generic [ref=e32]: Hudud
            - textbox "Hudud" [ref=e34] [cursor=pointer]:
              - /placeholder: Hududni tanlang
          - generic [ref=e35]:
            - generic [ref=e36]: Telefon raqami
            - textbox "Telefon raqami" [ref=e38]:
              - /placeholder: +998 90 123 45 67
              - text: "+998"
          - paragraph [ref=e39]: yoki
          - link "Qo‘ng‘iroq orqali yozilish" [ref=e40] [cursor=pointer]:
            - /url: tel:+998555559999
            - generic [ref=e44]: Qo‘ng‘iroq orqali yozilish
      - button "Diagnostikaga yozilish" [ref=e46] [cursor=pointer]:
        - generic [ref=e48]: Diagnostikaga yozilish
```
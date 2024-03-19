---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
draft: false
sections:
  - title: "Appetizers"
    items:
      - name: "Caprese Salad"
        description: "Fresh tomatoes, mozzarella cheese, basil, olive oil, and balsamic glaze."
        price: "$10"
      - name: "Stuffed Mushrooms"
        description: "Large mushroom caps stuffed with cheese, garlic, and herbs."
        price: "$12"
  - title: "Main Course"
    items:
      - name: "Grilled Salmon"
        description: "Fresh grilled salmon served with roasted vegetables and lemon butter sauce."
        price: "$25"
      - name: "Filet Mignon"
        description: "Tender filet mignon cooked to perfection, served with mashed potatoes."
        price: "$35"
---
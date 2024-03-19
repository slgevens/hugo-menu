---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
draft: false
sections:
  - title: "Appetizers"
    items:
      - name: "Caprese Salad"
        description: "Fresh tomatoes, mozzarella cheese, basil, olive oil, and balsamic glaze."
      - name: "Stuffed Mushrooms"
        description: "Large mushroom caps stuffed with cheese, garlic, and herbs."
  - title: "Main Course"
    items:
      - name: "Grilled Salmon"
        description: "Fresh grilled salmon served with roasted vegetables and lemon butter sauce."
      - name: "Filet Mignon"
        description: "Tender filet mignon cooked to perfection, served with mashed potatoes."
---
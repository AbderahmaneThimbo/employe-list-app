<template>
     <div class="employee-list-container">
         <ol class="employee-list">
            <li class="employee-item">Mangasouba</li>
            <li class="employee-item">Ousmane Ly</li>
            <li class="employee-item">Zubeir Ba</li>
        </ol>
    </div>

  </template>
  
  <script>

  </script>
  
  <style scoped>
  .employee-list-container {
  padding: 20px;
  max-width: 600px;
  margin: 0 auto;
}

.employee-list {
  list-style: decimal inside;
  padding-left: 0;
  margin: 0;
  background: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 8px;
}

.employee-item {
  padding: 10px;
  border-bottom: 1px solid #ddd;
  transition: background-color 0.3s ease;
}

.employee-item:last-child {
  border-bottom: none;
}

.employee-item:hover {
  background-color: #e0e0e0;
  cursor: pointer;
}

  </style>
  

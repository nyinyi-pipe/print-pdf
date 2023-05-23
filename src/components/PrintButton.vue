<template>
    <button @click="printPdf">Print PDF</button>
  </template>
  
  <script>
  import jsPDF from 'jspdf';
  
  export default {
    methods: {
      printPdf() {
        const doc = new jsPDF();
        doc.text('xxxxx eSignature Test xxxxx', 10, 10);
        doc.save('eSign01.pdf');
      },
    },
  };
  </script>
  
  <style scoped>
  button {
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  </style>
  
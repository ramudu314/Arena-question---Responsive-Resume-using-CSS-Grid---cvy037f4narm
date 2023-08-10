.main-content {
  display: grid;
  grid-template-columns: 300px 700px;
  min-height: 1000px;
}

.left-section {
  grid-column: span 1
  background-color: lightblue;
}

.right-section {
  grid-column:span 1 / span 2;
  width: 90%;
  background-color: lightgreen;
}



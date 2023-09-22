.bouquet {
  position: relative;
  width: 200px;
  height: 300px;
  margin: auto;
}

.flower {
  position: absolute;
  width: 50px;
  height: 50px;
  border-radius: 50%;
}

.yellow {
  background-color: yellow;
}

.stem {
  position: absolute;
  bottom: 0;
  left: calc(50% - 5px);
  width: 10px;
  height: 200px;
  background-color: green;
}

.yellow:nth-child(1) {
  top: -10px;
  left: calc(50% - 25px);
}

.yellow:nth-child(2) {
  top: -10px;
  right: calc(50% - 25px);
}

.yellow:nth-child(3) {
  top: calc(50% - 25px);
  left: -10px;
}

.yellow:nth-child(4) {
  top: calc(50% - 25px);
  right: -10px;
}

.yellow:nth-child(5) {
  bottom: -10px;
  left: calc(50% - 25px);
}

.yellow:nth-child(6) {
  bottom: -10px;
  right: calc(50% - 25px);
}

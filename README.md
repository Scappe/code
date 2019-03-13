class Personaggi {
  Personaggi(int x, int y) {

    }
        PShape ron;
    int ronXposition=200;
    void disegna() {
      ron = loadShape("ron.obj");
      shape (ron, ronXposition, 600);
  }
}
Personaggi ron;
void setup() {
  fullScreen(P3D);
   ron = new Personaggi(100, 100);
}

void draw() {
  background(0, 0, 255);
  lights();
}

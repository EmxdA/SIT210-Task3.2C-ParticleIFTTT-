# SIT210-Task3.2C-ParticleIFTTT-

double lightVal = 300;

void setup() {
    Particle.variable("light", &lightVal, DOUBLE);
}

void loop() {
    lightVal = lightVal + 34.4;
    delay(3000);

}

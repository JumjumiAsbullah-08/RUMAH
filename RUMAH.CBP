# RUMAH
TUGAS GRAFIK KOMPUTER MENGGAMBAR RUMAH 2D MENGGUNAKAN CODE BLOCK OPEN GL

#include<Windows.h>
#include<GL\glut.h>
void init()
{
    glClearColor(2, 1, 12, 0);
    glMatrixMode(GL_PROJECTION);
    gluOrtho2D(0.7, 800, 0.0, 600);
}
void home()
{
    glClear(GL_COLOR_BUFFER_BIT);
    glColor3f(0.3, 0.5, 0.8);
    glBegin(GL_POLYGON);
    glVertex2i(200, 500);
    glVertex2i(600, 500);
    glVertex2i(700, 350);
    glVertex2i(300, 350);
    glEnd();

    glColor3f(0.1, 0.5, 0.0);
    glBegin(GL_TRIANGLES);
    glVertex2i(200, 500);
    glVertex2i(100, 350);
    glVertex2i(300, 350);
    glEnd();

    glColor3f(0.7, 0.2, 0.3);
    glBegin(GL_POLYGON);
    glVertex2i(100, 350);
    glVertex2i(300, 350);
    glVertex2i(300, 100);
    glVertex2i(100, 100);
    glEnd();

    glColor3f(0.7, 0.2, 0.9);
    glBegin(GL_POLYGON);
    glVertex2i(150, 250);
    glVertex2i(250, 250);
    glVertex2i(250, 100);
    glVertex2i(150, 100);
    glEnd();


    glColor3f(0.3, 0.7, 0.9);
    glPointSize(15);
    glBegin(GL_POINTS);
    glVertex2i(170, 170);
    glEnd();

    glColor3f(0.1, 0.2, 0.3);
    glBegin(GL_POLYGON);
    glVertex2i(300, 350);
    glVertex2i(700, 350);
    glVertex2i(700, 100);
    glVertex2i(300, 100);
    glEnd();

    glColor3f(0.2, 0.4, 0.3);
    glBegin(GL_POLYGON);
    glVertex2i(330, 320);
    glVertex2i(450, 320);
    glVertex2i(450, 230);
    glVertex2i(330, 230);
    glEnd();

    glColor3f(0.1, 0.7, 0.5);
    glLineWidth(5);
    glBegin(GL_LINES);
    glVertex2i(390, 320);
    glVertex2i(390, 230);
    glVertex2i(330, 273);
    glVertex2i(450, 273);
    glEnd();

    glColor3f(0.2, 0.4, 0.3);
    glBegin(GL_POLYGON);
    glVertex2i(530, 320);
    glVertex2i(650, 320);
    glVertex2i(650, 230);
    glVertex2i(530, 230);
    glEnd();

    glColor3f(0.1, 0.7, 0.5);
    glLineWidth(5);
    glBegin(GL_LINES);
    glVertex2i(590, 320);
    glVertex2i(590, 230);
    glVertex2i(530, 273);
    glVertex2i(650, 273);
    glEnd();


    glColor3f(0.3, 0.5, 0.7);
    glLineWidth(3);
    glBegin(GL_POLYGON);
    glVertex2i(150, 100);
    glVertex2i(250, 100);
    glVertex2i(210, 0);
    glVertex2i(40, 0);
    glEnd();
    glFlush();
}
int main(int argc, char ** argv)
{
    glutInit(&argc, argv);
    glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB);
    glutInitWindowPosition(100, 100);
    glutInitWindowSize(500, 500);
    glutCreateWindow("Rumah 2D dengan Metode OpenGL");
    init();
    glutDisplayFunc(home);
    glutMainLoop();
}


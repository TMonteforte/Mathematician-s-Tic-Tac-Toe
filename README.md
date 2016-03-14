// Mathematician-s-Tic-Tac-Toe
// An interactive Java implementation of Mathematician's Tic-Tac-Toe

import javax.swing.*;
import java.awt.*;

public class Mathematicians_Tic_Tac_Toe {

  private JFrame f;
  private JPanel p;
  private JButton b1;
  private JLabel lab;
  
  
  public Mathematicians_Tic_Tac_Toe() {
  gui();
  }
  
  public void gui() {
  
  f = new JFrame("Mathematician\'s Tic-Tac-Toe");
  f.setVisible(true);
  f.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
  
  p = new JPanel();

  b1 = new JButton("Test");
  lab = new JLabel("This is a test label");
  
  p.add(b1);
  p.add(lab);
  
  f.add(p);
  }
  
  public static void main (String[] args) {
  new Mathematicians_Tic_Tac_Toe();
  }
}

# testFile

import java.awt.FlowLayout;
import javax.swing.*;
import java.awt.*;
import javax.swing.JButton;
import javax.swing.JFrame;



public class Main extends JFrame{
		private static final long serialVersionUID=1L;
		public static void main(String[] args){
			new Main().setVisible(true);	
		}
		private Main(){
			super("Tutorial");
			setSize(200,200);//1024x768
			setResizable(false);
			setDefaultCloseOperation(EXIT_ON_CLOSE);
			setLayout(new FlowLayout());
			JPanel p=new JPanel();
			p.setBackground(Color.GREEN);
			JLabel l=new JLabel("Tutorial");
			JButton button=new JButton("PUSH");
			add(button);//adds to frame
		}
}

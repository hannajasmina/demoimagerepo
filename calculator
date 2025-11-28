import javax.swing.*;
import java.awt.event.*;

public class SimpleLogin {
    public static void main(String[] args) {
        JFrame f = new JFrame("Login Form");
        
        JLabel l1 = new JLabel("Username:");
        JLabel l2 = new JLabel("Password:");
        JTextField t1 = new JTextField();
        JPasswordField t2 = new JPasswordField();
        JButton b = new JButton("Login");
        
        l1.setBounds(30, 30, 80, 30);
        l2.setBounds(30, 70, 80, 30);
        t1.setBounds(120, 30, 150, 30);
        t2.setBounds(120, 70, 150, 30);
        b.setBounds(120, 110, 80, 30);
        
        f.add(l1); f.add(l2); f.add(t1); f.add(t2); f.add(b);
        
        f.setSize(320, 200);
        f.setLayout(null);
        f.setVisible(true);
        f.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        
        b.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                String user = t1.getText();
                String pass = new String(t2.getPassword());
                
                if (user.equals("admin") && pass.equals("1234"))
                    JOptionPane.showMessageDialog(f, "Login Successful!");
                else
                    JOptionPane.showMessageDialog(f, "Invalid username or password!");
            }
        });
    }
}

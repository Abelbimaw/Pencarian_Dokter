# Modul9_array
# Array 1
![Image SS1](https://github.com/Abelbimaw/Modul9_array/blob/master/code1.PNG)
![Image SS1](https://github.com/Abelbimaw/Modul9_array/blob/master/array%201.PNG)

# Array 2
![Image SS2](https://github.com/Abelbimaw/Modul9_array/blob/master/code2.PNG)
![Image SS2](https://github.com/Abelbimaw/Modul9_array/blob/master/array%202.PNG)

# Array 3
![Image SS3](https://github.com/Abelbimaw/Modul9_array/blob/master/code3.PNG)
![Image SS3](https://github.com/Abelbimaw/Modul9_array/blob/master/array%203.PNG)

# Testarray2
![Image SS4](https://github.com/Abelbimaw/Modul9_array/blob/master/code4.PNG)
![Image SS4](https://github.com/Abelbimaw/Modul9_array/blob/master/testarraydua.PNG)

# PemilihanDokter
    
    public class PemilihanDokter extends javax.swing.JFrame {
   
    /**
     * Creates new form PemilihanDokter
     */
    public PemilihanDokter() {
        initComponents();
    }

    /**
     * This method is called from within the constructor to initialize the form.
     * WARNING: Do NOT modify this code. The content of this method is always
     * regenerated by the Form Editor.
     */
    @SuppressWarnings("unchecked")
    
    private void jcoDokActionPerformed(java.awt.event.ActionEvent evt) {                                       
        // TODO add your handling code here:
        if(jcoDok.getSelectedItem().equals("Dr.Abbas")){
            tbNama.setText("Dr.Abbas");
            tbAlamat.setText("Jl.Sinisitu");
            tbUsia.setText("23 Tahun");
            tbJk.setText("Laki-Laki");
            tbGd.setText("A");
            tbStatus.setText("Belum Menikah");
            tbKewa.setText("Abu Dabi");
            tbwaktu.setText("Pagi (5 AM - 4 PM)");
            tbdokter.setText("Dokter Jantung");
        }
        else 
        if(jcoDok.getSelectedItem().equals("Dr.Bejo")){
            tbNama.setText("Dr.Bejo");
            tbAlamat.setText("Jl.AlwaysBejo");
            tbUsia.setText("21 Tahun");
            tbJk.setText("Laki-Laki");
            tbGd.setText("O");
            tbStatus.setText("Belum Menikah");
            tbKewa.setText("Indonesia");
            tbwaktu.setText("Pagi (4 AM - 5 PM)");
            tbdokter.setText("Dokter Umum");
        }
        else 
        if(jcoDok.getSelectedItem().equals("Dr.Ini")){
            tbNama.setText("Dr.Ini Puji Astutik");
            tbAlamat.setText("Jl.Cendana, Papua");
            tbUsia.setText("20 Tahun");
            tbJk.setText("Perempuan");
            tbGd.setText("B");
            tbStatus.setText("Belum Menikah");
            tbKewa.setText("Indonesia");
            tbwaktu.setText("Pagi (7 AM - 3PM)");
            tbdokter.setText("Dokter Kecantikan");
        }
    }                                      

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(PemilihanDokter.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(PemilihanDokter.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(PemilihanDokter.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(PemilihanDokter.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new PemilihanDokter().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabel14;
    private javax.swing.JLabel jLabel15;
    private javax.swing.JLabel jLabel16;
    private javax.swing.JLabel jLabel17;
    private javax.swing.JLabel jLabel18;
    private javax.swing.JLabel jLabel19;
    private javax.swing.JLabel jLabel2;
    private javax.swing.JLabel jLabel20;
    private javax.swing.JLabel jLabel21;
    private javax.swing.JLabel jLabel22;
    private javax.swing.JPanel jPanel1;
    private javax.swing.JPanel jPanel2;
    private javax.swing.JComboBox<String> jcoDok;
    private javax.swing.JTextField tbAlamat;
    private javax.swing.JTextField tbGd;
    private javax.swing.JTextField tbJk;
    private javax.swing.JTextField tbKewa;
    private javax.swing.JTextField tbNama;
    private javax.swing.JTextField tbStatus;
    private javax.swing.JTextField tbUsia;
    private javax.swing.JTextField tbdokter;
    private javax.swing.JTextField tbwaktu;
    // End of variables declaration                   
}

![Image SS5](https://github.com/Abelbimaw/Modul9_array/blob/master/PemilihanDokter.PNG)
![Image SS6](https://github.com/Abelbimaw/Modul9_array/blob/master/PemilihanDokter%201.PNG)

# Pencariaan Sederhana Naik  (Praktikum 1)
    import java.*;
    import javax.swing.*;

    public class Pencarian_Sederhana_naik {
        public static void main (String []args){
            try {
                int[] DataArray={0,1,2,3,4,5,6,7,8,9,10};
                int i, NilaiX;
                boolean ketemu;

                System.out.println("");
                System.out.println("Program Pencarina Data Sederhana");
                System.out.println("================================");
                System.out.println("");

               //menampilkan nilai array
                    for(i=0;i<11;i++)
                    System.out.print(DataArray[i]+" ");
                    System.out.print("");
                    System.out.println("");

                    // Masukan Data yang Di cari
                        String bilangan=JOptionPane.showInputDialog("Masukan nilai yang kamu cari??");
                        NilaiX =Integer.parseInt(bilangan);
                        System.out.println("");
                        System.out.println("data yang di cari adalah="+NilaiX);
                        ketemu=false;
                        for(i=0;i<11;i++){
                            if(DataArray[i]==NilaiX)
                            {
                                ketemu=true;
                                break;
                            }
                        } 

                    System.out.println("=============================");
                    System.out.println("");
                    if(ketemu==true){
                        System.out.println("Data di temukan pada elemen ke"+ (i+1));
                    } else{
                        System.out.println("Data tidak di temukan ");
                        System.out.println("~~~~~~~~~~~~~~~~~~~~~`");
                        System.out.println("");
                        System.out.println("");
                        System.out.println("");
                        System.exit(0);            
                    }

            } catch (NullPointerException e){
                System.out.println("NPE");}

        }
    }
![Image SS7](https://github.com/Abelbimaw/Modul9_array/blob/master/pencarian%201.PNG)
![Image SS8](https://github.com/Abelbimaw/Modul9_array/blob/master/pencarian%202.PNG)
![Image SS9](https://github.com/Abelbimaw/Modul9_array/blob/master/pencarian%203.PNG)
![Image SS10](https://github.com/Abelbimaw/Modul9_array/blob/master/pencarian%204.PNG)

# PeminjamanBuku (Praktikum2)
![Image SS11](https://github.com/Abelbimaw/Modul9_array/blob/master/code9.PNG)
![Image SS12](https://github.com/Abelbimaw/Modul9_array/blob/master/prak2%201.PNG)
![Image SS13](https://github.com/Abelbimaw/Modul9_array/blob/master/prak2%202.PNG)

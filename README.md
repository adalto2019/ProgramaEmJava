# ProgramaEmJava
Aqui foi desenvolvido uma janela com **Java Swing** contendo uma lista de botões com todos os hospitais
públicos e conveniados, com informações relevantes de cada um deles, como: nome completo do hospital,
endereço, telefone, horário de funcionamento, data de fundação e etc. Ao clicar no botão correspondente
a cada unidade hospitalar o usuário irá visulaizar as informações referente a essa unidade.

## Layout do Projeto
<img src="ProgrmaEmJava.png">
<img src="ProgrmaEmJava2.png">


## Tecnologias Utilizadas
Front End: Java, API Java Swing. 

## Inspecionando o Código

```
package exercicio.java;

public class OlaMundoJava extends javax.swing.JFrame {
    public OlaMundoJava() {
        initComponents();
    }
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {
        jPasswordField1 = new javax.swing.JPasswordField();
        lblMensagem = new javax.swing.JLabel();
        btnCliqueHSCM = new javax.swing.JButton();
        btnCliqueHELV = new javax.swing.JButton();
        btnCliqueHGF = new javax.swing.JButton();
        btnCliqueEGCC = new javax.swing.JButton();
        jLabel1 = new javax.swing.JLabel();
        btnCliqueSOPAI = new javax.swing.JButton();
        btnCliqueHIF = new javax.swing.JButton();
        btnCliquePraxis = new javax.swing.JButton();
        btnCliqueHGWA = new javax.swing.JButton();
        btnCliqueIJF = new javax.swing.JButton();
        btnCliqueHSJ = new javax.swing.JButton();
        btnCliqueHSM = new javax.swing.JButton();
        btnCliqueHMSJ1 = new javax.swing.JButton();
        btnCliqueHUWC = new javax.swing.JButton();
        btnCliqueProntocardio = new javax.swing.JButton();
        btnCliqueHFT = new javax.swing.JButton();
        btnCliqueHPM = new javax.swing.JButton();
        btnCliqueHMZA = new javax.swing.JButton();
        btnCliqueHMeniJesus = new javax.swing.JButton();

        jPasswordField1.setText("jPasswordField1");

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);
        setBackground(new java.awt.Color(255, 153, 0));

        lblMensagem.setBackground(new java.awt.Color(255, 153, 51));
        lblMensagem.setFont(new java.awt.Font("Segoe UI Historic", 0, 18)); // NOI18N
        lblMensagem.setForeground(new java.awt.Color(0, 0, 0));
        lblMensagem.setHorizontalAlignment(javax.swing.SwingConstants.LEFT);
        lblMensagem.setText("Clique na sigla do hospital para obter informações ...");
        lblMensagem.setToolTipText("");

        btnCliqueHSCM.setBackground(new java.awt.Color(0, 204, 102));
        btnCliqueHSCM.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHSCM.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHSCM.setText("HSCM");
        btnCliqueHSCM.setActionCommand("HGF");
        btnCliqueHSCM.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHSCMActionPerformed(evt);
            }
        });

        btnCliqueHELV.setBackground(new java.awt.Color(255, 153, 0));
        btnCliqueHELV.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHELV.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHELV.setText("HELV");
        btnCliqueHELV.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHELVActionPerformed(evt);
            }
        });

        btnCliqueHGF.setBackground(new java.awt.Color(153, 153, 255));
        btnCliqueHGF.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHGF.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHGF.setText("HGF");
        btnCliqueHGF.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHGFActionPerformed(evt);
            }
        });

        btnCliqueEGCC.setBackground(new java.awt.Color(204, 153, 0));
        btnCliqueEGCC.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueEGCC.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueEGCC.setText("HGCC");
        btnCliqueEGCC.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueEGCCActionPerformed(evt);
            }
        });

        jLabel1.setBackground(new java.awt.Color(204, 255, 204));
        jLabel1.setFont(new java.awt.Font("Segoe UI", 3, 18)); // NOI18N
        jLabel1.setForeground(new java.awt.Color(255, 0, 0));
        jLabel1.setText(" INFORMAÇÕES HOSPITAIS PÚBLICOS DE FORTALEZA ");
        jLabel1.setBorder(javax.swing.BorderFactory.createLineBorder(new java.awt.Color(255, 153, 0)));

        btnCliqueSOPAI.setBackground(new java.awt.Color(153, 255, 153));
        btnCliqueSOPAI.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueSOPAI.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueSOPAI.setText("SOPAI");
        btnCliqueSOPAI.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueSOPAIActionPerformed(evt);
            }
        });

        btnCliqueHIF.setBackground(new java.awt.Color(255, 255, 102));
        btnCliqueHIF.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHIF.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHIF.setText("HIF ");
        btnCliqueHIF.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHIFActionPerformed(evt);
            }
        });

        btnCliquePraxis.setBackground(new java.awt.Color(102, 102, 102));
        btnCliquePraxis.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliquePraxis.setForeground(new java.awt.Color(0, 51, 51));
        btnCliquePraxis.setText("INST. PRAXIS");
        btnCliquePraxis.setActionCommand("HGF");
        btnCliquePraxis.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliquePraxisActionPerformed(evt);
            }
        });

        btnCliqueHGWA.setBackground(new java.awt.Color(153, 153, 0));
        btnCliqueHGWA.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHGWA.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHGWA.setText("HGWA");
        btnCliqueHGWA.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHGWAActionPerformed(evt);
            }
        });

        btnCliqueIJF.setBackground(new java.awt.Color(255, 51, 51));
        btnCliqueIJF.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueIJF.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueIJF.setText("IJF ");
        btnCliqueIJF.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueIJFActionPerformed(evt);
            }
        });

        btnCliqueHSJ.setBackground(new java.awt.Color(153, 153, 153));
        btnCliqueHSJ.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHSJ.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHSJ.setText("HSJ ");
        btnCliqueHSJ.setActionCommand("HGF");
        btnCliqueHSJ.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHSJActionPerformed(evt);
            }
        });

        btnCliqueHSM.setBackground(new java.awt.Color(0, 153, 153));
        btnCliqueHSM.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHSM.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHSM.setText("HSM");
        btnCliqueHSM.setActionCommand("HGF");
        btnCliqueHSM.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHSMActionPerformed(evt);
            }
        });

        btnCliqueHMSJ1.setBackground(new java.awt.Color(153, 0, 153));
        btnCliqueHMSJ1.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHMSJ1.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHMSJ1.setText("HMSJ");
        btnCliqueHMSJ1.setActionCommand("HGF");
        btnCliqueHMSJ1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHMSJ1ActionPerformed(evt);
            }
        });

        btnCliqueHUWC.setBackground(new java.awt.Color(255, 153, 153));
        btnCliqueHUWC.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHUWC.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHUWC.setText("HUWC");
        btnCliqueHUWC.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHUWCActionPerformed(evt);
            }
        });

        btnCliqueProntocardio.setBackground(new java.awt.Color(255, 255, 255));
        btnCliqueProntocardio.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueProntocardio.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueProntocardio.setText("Prontocárdio");
        btnCliqueProntocardio.setActionCommand("HGF");
        btnCliqueProntocardio.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueProntocardioActionPerformed(evt);
            }
        });

        btnCliqueHFT.setBackground(new java.awt.Color(255, 0, 102));
        btnCliqueHFT.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHFT.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHFT.setText("HFT");
        btnCliqueHFT.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHFTActionPerformed(evt);
            }
        });

        btnCliqueHPM.setBackground(new java.awt.Color(0, 153, 204));
        btnCliqueHPM.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHPM.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHPM.setText("HPM");
        btnCliqueHPM.setActionCommand("HGF");
        btnCliqueHPM.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHPMActionPerformed(evt);
            }
        });

        btnCliqueHMZA.setBackground(new java.awt.Color(153, 255, 255));
        btnCliqueHMZA.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHMZA.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHMZA.setText("Hmza");
        btnCliqueHMZA.setToolTipText("");
        btnCliqueHMZA.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHMZAActionPerformed(evt);
            }
        });

        btnCliqueHMeniJesus.setBackground(new java.awt.Color(255, 0, 153));
        btnCliqueHMeniJesus.setFont(new java.awt.Font("Segoe UI", 1, 18)); // NOI18N
        btnCliqueHMeniJesus.setForeground(new java.awt.Color(0, 51, 51));
        btnCliqueHMeniJesus.setText("H. Men. Jesus");
        btnCliqueHMeniJesus.setActionCommand("HGF");
        btnCliqueHMeniJesus.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnCliqueHMeniJesusActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(jLabel1)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(6, 6, 6)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                            .addComponent(lblMensagem, javax.swing.GroupLayout.PREFERRED_SIZE, 441, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addGroup(layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING, false)
                                    .addComponent(btnCliqueHSM, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                    .addComponent(btnCliqueHELV, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                    .addComponent(btnCliqueHSJ, javax.swing.GroupLayout.Alignment.LEADING, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                    .addComponent(btnCliqueHPM, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(btnCliqueHMeniJesus, javax.swing.GroupLayout.PREFERRED_SIZE, 166, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addGroup(layout.createSequentialGroup()
                                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                            .addGroup(layout.createSequentialGroup()
                                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                                    .addComponent(btnCliqueHSCM, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                                    .addComponent(btnCliqueHMSJ1, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                                                .addGap(12, 12, 12)
                                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                                    .addGroup(layout.createSequentialGroup()
                                                        .addComponent(btnCliqueHGF)
                                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                                        .addComponent(btnCliqueEGCC))
                                                    .addGroup(layout.createSequentialGroup()
                                                        .addComponent(btnCliqueHIF, javax.swing.GroupLayout.PREFERRED_SIZE, 72, javax.swing.GroupLayout.PREFERRED_SIZE)
                                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                                        .addComponent(btnCliqueIJF, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))))
                                            .addGroup(layout.createSequentialGroup()
                                                .addComponent(btnCliquePraxis, javax.swing.GroupLayout.PREFERRED_SIZE, 166, javax.swing.GroupLayout.PREFERRED_SIZE)
                                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                                .addComponent(btnCliqueHFT, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                                            .addGroup(layout.createSequentialGroup()
                                                .addComponent(btnCliqueProntocardio, javax.swing.GroupLayout.PREFERRED_SIZE, 166, javax.swing.GroupLayout.PREFERRED_SIZE)
                                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                                .addComponent(btnCliqueHMZA, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)))
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                            .addComponent(btnCliqueSOPAI, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                            .addComponent(btnCliqueHGWA, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                            .addComponent(btnCliqueHUWC, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))))))))
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                .addGap(21, 21, 21)
                .addComponent(jLabel1)
                .addGap(69, 69, 69)
                .addComponent(lblMensagem, javax.swing.GroupLayout.PREFERRED_SIZE, 310, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(btnCliqueHSCM)
                    .addComponent(btnCliqueHGF)
                    .addComponent(btnCliqueEGCC)
                    .addComponent(btnCliqueHELV)
                    .addComponent(btnCliqueSOPAI))
                .addGap(18, 18, 18)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(btnCliqueHIF)
                    .addComponent(btnCliqueHSJ)
                    .addComponent(btnCliqueHMSJ1)
                    .addComponent(btnCliqueIJF)
                    .addComponent(btnCliqueHGWA))
                .addGap(18, 18, 18)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(btnCliqueHSM)
                    .addComponent(btnCliquePraxis)
                    .addComponent(btnCliqueHUWC)
                    .addComponent(btnCliqueHFT))
                .addGap(18, 18, 18)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(btnCliqueProntocardio)
                    .addComponent(btnCliqueHPM)
                    .addComponent(btnCliqueHMZA))
                .addGap(18, 18, 18)
                .addComponent(btnCliqueHMeniJesus)
                .addContainerGap(34, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        

    private void btnCliqueHSCMActionPerformed(java.awt.event.ActionEvent evt) {                                              
        lblMensagem.setText("<html>"
                + "<br>Santa Casa da Misericórdia de Fortaleza"
                + "<br>Endereço: R. Barão do Rio Branco, 20 - Centro, Fortaleza - CE, 60025-060"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3455-9126"
                + "<br>Inauguração: 12 de março de 1861"
                + "<br>"
                + "<br>Necessita de AIH: 03 VIAS"
                + "</html>");
    }                                             

    private void btnCliqueHELVActionPerformed(java.awt.event.ActionEvent evt) {                                              
        lblMensagem.setText("<html>"
                + "<br>Hospital Estadual Leonardo Da Vinci"
                + "<br>Endereço: R. Rocha Lima, 1563 - Aldeota, Fortaleza - CE, 60135-285"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone: (85)3433-1032"
                + "<br>Inauguração: --- "
                + "</html>");
    }                                             

    private void btnCliqueHGFActionPerformed(java.awt.event.ActionEvent evt) {                                             
         lblMensagem.setText("<html>"
                + "<br>Hospital Geral de Fortaleza"
                + "<br>Endereço: R. Ávila Goularte, 900 - Papicu, Fortaleza - CE, 60150-160"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3101-3209"
                + "<br>Inauguração: 23 de Maio de 1969"
                + "</html>");
    }                                            

    private void btnCliqueEGCCActionPerformed(java.awt.event.ActionEvent evt) {                                              
        lblMensagem.setText("<html>"
                + "<br>Hospital Geral Dr. César Cals"
                + "<br>Endereço: Avenida Imperador, 545 - Centro, Fortaleza - CE, 60015-152"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3101-5404"
                + "<br>Inauguração: 31 de Outubro de 1928"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                             

    private void btnCliqueSOPAIActionPerformed(java.awt.event.ActionEvent evt) {                                               
        lblMensagem.setText("<html>"
                + "<br>Hospital Infantil Filantrópico"
                + "<br>Endereço: Av. Francisco Sá, 5036 - Carlito Pamplona, Fortaleza - CE, 60310-002"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)4005-0707"
                + "<br>Inauguração: 25 de Maio de 1959"
                + "</html>");
    }                                              

    private void btnCliqueHIFActionPerformed(java.awt.event.ActionEvent evt) {                                             
        lblMensagem.setText("<html>"
                + "<br>Hospital Infantil de Fortaleza"
                + "<br>Endereço: Av. Lineu Machado, 155 - Jóquei Clube, Fortaleza - CE, 60520-101"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)2180-6706"
                + "<br>Inauguração: 17 de Agosto de 2020"
                + "</html>");
    }                                            

    private void btnCliquePraxisActionPerformed(java.awt.event.ActionEvent evt) {                                                
        lblMensagem.setText("<html>"
                + "<br>Instituto Práxis"
                + "<br>Endereço: Av. Francisco Sá, 5445 - Álvaro Weyne, Fortaleza - CE, 60310-002"
                + "<br>Horas: SEG a SEX - 07:00 às 17:00 (Exceto Fériados)"
                + "<br>Telefone:(85)3284-3636"
                + "<br>Inauguração: 06 de Janeiro de 2003"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                               

    private void btnCliqueHGWAActionPerformed(java.awt.event.ActionEvent evt) {                                              
        lblMensagem.setText("<html>"
                + "<br>Hospital Geral Waldemar Alcântara"
                + "<br>Endereço: Rua Dr. Pergentino Maia, 1559 - Messejana, Fortaleza - CE, 60864-040"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3216-8300"
                + "<br>Inauguração: 26 de Dezembro de 2002,"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS (Pediátria)"
                + "</html>");
    }                                             

    private void btnCliqueIJFActionPerformed(java.awt.event.ActionEvent evt) {                                             
        lblMensagem.setText("<html>"
                + "<br>Instituto Doutor José Frota"
                + "<br>Endereço: R. Barão do Rio Branco, 1816 - Centro, Fortaleza - CE, 60025-061"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone: (85) 3255-5000"
                + "<br>Inauguração: 13 de Dezembro de 1932,"
                + "</html>");
    }                                            

    private void btnCliqueHSJActionPerformed(java.awt.event.ActionEvent evt) {                                             
        lblMensagem.setText("<html>"
                + "<br>Hospital São José de Doenças Infecciosas"
                + "<br>R. Nestor Barbosa, 315 - Parquelândia, Fortaleza - CE, 60455-610"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone: (85) 0000-0000"
                + "<br>Inauguração: 08 de Novembro de 1936,"
                + "</html>");

    }                                            

    private void btnCliqueHSMActionPerformed(java.awt.event.ActionEvent evt) {                                             
        lblMensagem.setText("<html>"
                + "<br>Hospital de Saúde Mental Professor Frota Pinto"
                + "<br>Endereço: Rua Vicente Nobre Macêdo, S/n - Messejana, Fortaleza - CE, 60841-110"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3101-4348"
                + "<br>Inauguração: --- "
                + "</html>");
    }                                            

    private void btnCliqueHMSJ1ActionPerformed(java.awt.event.ActionEvent evt) {                                               
        lblMensagem.setText("<html>"
                + "<br>Hospital do Coração de Messejana"
                + "<br>Endereço: Av. Frei Cirilo, 3480 - Cajazeiras, Fortaleza - CE, 60840-285"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3101-4151"
                + "<br>Inauguração: 1º de Maio de 1933,"
                + "</html>");
    }                                              

    private void btnCliqueHUWCActionPerformed(java.awt.event.ActionEvent evt) {                                              
        lblMensagem.setText("<html>"
                + "<br>Hospital Universitário Walter Cantídio"
                + "<br>Endereço: R. Pastor Samuel Munguba, 1290 - Rodolfo Teófilo, Fortaleza - CE, 60430-372"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3366-8167"
                + "<br>Inauguração: 1959,"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                             

    private void btnCliqueProntocardioActionPerformed(java.awt.event.ActionEvent evt) {                                                      
        lblMensagem.setText("<html>"
                + "<br>Hospital Prontocardio"
                + "<br>Endereço: Av. Barão de Studart, 560 - Meireles, Fortaleza - CE, 60120-000"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3466-3000"
                + "<br>Inauguração: 1979"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                                     

    private void btnCliqueHFTActionPerformed(java.awt.event.ActionEvent evt) {                                             
       lblMensagem.setText("<html>"
                + "<br>Hospital Fernandes Távora"
                + "<br>Endereço: Av. Francisco Sá, 5445 - Álvaro Weyne, Fortaleza - CE, 60335-195"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3228-2555"
                + "<br>Inauguração: 26 de Julho de 1974"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                            

    private void btnCliqueHPMActionPerformed(java.awt.event.ActionEvent evt) {                                             
        lblMensagem.setText("<html>"
                + "<br>Hospital Da Polícia Militar"
                + "<br>Endereço: Rua Princesa Isabel, 1526 - Farias Brito, Fortaleza - CE, 60015-061"
                + "<br>Horas: ---"
                + "<br>Telefone:(85)3101-4976"
                + "<br>Inauguração: ---"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                            

    private void btnCliqueHMZAActionPerformed(java.awt.event.ActionEvent evt) {                                              
        lblMensagem.setText("<html>"
                + "<br>Hospital e Maternidade Dra. Zilda Arns Neumann (Hospital da Mulher de Fortaleza)"
                + "<br>Endereço: R. George Rocha, 50 - Demócrito Rocha, Fortaleza - CE, 60520-100"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3233-3896"
                + "<br>Inauguração: 17 de Agosto de 2012"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                             

    private void btnCliqueHMeniJesusActionPerformed(java.awt.event.ActionEvent evt) {                                                    
        lblMensagem.setText("<html>"
                + "<br>Hospital Menino Jesus"
                + "<br>Endereço: Rua Germano Franck, 734 - Parangaba, Fortaleza - CE, 60740-020"
                + "<br>Horas: Aberto 24 horas"
                + "<br>Telefone:(85)3225-1666"
                + "<br>Inauguração: ---"
                + "<br>"
                + "<br>Necessita de AIH: 02 VIAS"
                + "</html>");
    }                                                   

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new OlaMundoJava().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton btnCliqueEGCC;
    private javax.swing.JButton btnCliqueHELV;
    private javax.swing.JButton btnCliqueHFT;
    private javax.swing.JButton btnCliqueHGF;
    private javax.swing.JButton btnCliqueHGWA;
    private javax.swing.JButton btnCliqueHIF;
    private javax.swing.JButton btnCliqueHMSJ1;
    private javax.swing.JButton btnCliqueHMZA;
    private javax.swing.JButton btnCliqueHMeniJesus;
    private javax.swing.JButton btnCliqueHPM;
    private javax.swing.JButton btnCliqueHSCM;
    private javax.swing.JButton btnCliqueHSJ;
    private javax.swing.JButton btnCliqueHSM;
    private javax.swing.JButton btnCliqueHUWC;
    private javax.swing.JButton btnCliqueIJF;
    private javax.swing.JButton btnCliquePraxis;
    private javax.swing.JButton btnCliqueProntocardio;
    private javax.swing.JButton btnCliqueSOPAI;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JPasswordField jPasswordField1;
    private javax.swing.JLabel lblMensagem;
    // End of variables declaration                   
}
```
## Autor

:game_die: Adalto Carvalho Ribeiro Simão Jr - Nov.22

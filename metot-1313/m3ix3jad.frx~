using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace metot_1313
{
    public partial class Form1 : Form
    {
        Color renk = Color.Red;
        Color renk2 = Color.Green;
        public Form1()
        {
            InitializeComponent();
        }

        private void btnHesapla_Click(object sender, EventArgs e)
        {
            Sekil sekil1 = new Sekil();
            sekil1.uzunKenar = Convert.ToInt32(txtSayi1.Text);
            sekil1.kisaKenar = Convert.ToInt32(txtSayi1.Text);
            //sekil1.KareYaz();
            sekil1.sekilCiz(btnSekil,renk, renk2);
            sekil1.mesajDeğiştir(btnSekil, txtMesaj.Text);






            btnSekil.Width = Convert.ToInt32(txtSayi1.Text);
            btnSekil.Height = Convert.ToInt32(txtSayi2.Text);


            btnSekil.Text = txtMesaj.Text;
        }

        private void btnRenk_Click(object sender, EventArgs e)
        {
            colorDialog1.ShowDialog();
            renk = colorDialog1.Color;

            

        }

        private void btnRenk2_Click(object sender, EventArgs e)
        {
            colorDialog1.ShowDialog();
            renk = colorDialog1.Color;

        }
    }
}

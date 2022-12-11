# Week-3-Programming
Week 3 Programming code
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Module3Exercise2Project
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btnR_Click(object sender, EventArgs e)
        {
            label1.Text = button3.Text;  //Fixed the name of the label to show the correct text
        }

        private void btnRed_Click(object sender, EventArgs e)
        {
            label1.BackColor = btnRed.BackColor;
            label1.Text = btnRed.Text; //Fixed the name of the label to show the correct text

        }

        private void btnBlue_Click(object sender, EventArgs e)
        {
            label1.BackColor = button2.BackColor;
            label1.Text = button2.Text;  //Fixed the name of the label to show the correct text


        }

        private void btnL_Click(object sender, EventArgs e)
        {
            label1.Text = button4.Text;   //Fixed the name of the label to show the correct text

        }

        private void button5_Click(object sender, EventArgs e)
        {
            this.Close();
        }

     
        

    }
}

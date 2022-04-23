# menustrip
 
using System;
using System.Windows.Forms;
namespace manustrip107.cs
{
    public partial class Form2 : Form
    {
        public Form2()
        {
            InitializeComponent();
        }
         private void form1ToolStripMenuItem_Click(object sender, EventArgs e)
        {
            Form1 f1 = new Form1();
            f1.Show();
        }
   private void redToolStripMenuItem1_Click(object sender, EventArgs e)
        {
            this.BackColor = Color.Red;
        }
 private void greenToolStripMenuItem1_Click(object sender, EventArgs e)
 {
            this.BackColor = Color.Green;
        }
           private void blueToolStripMenuItem1_Click(object sender, EventArgs e)
        {
            this.BackColor = Color.Blue;
        }
 }  } 

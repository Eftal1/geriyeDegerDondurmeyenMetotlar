# geriyedegerdondurmeyenmetotlar
C# Geriye Değer Döndürmeyen Metotlar için küçük bir örnektir. 


namespace Metotlar_GDDondermeyen
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void temizle()
        {
            textBox1.Text = "";
            textBox2.Text = "";
            textBox3.Text = "";
            textBox4.Text = "";
            textBox1.Focus();
        }
        void renklendir()
        {
            textBox1.BackColor = Color.Green; 
            textBox2.BackColor = Color.Blue; 
            textBox3.BackColor = Color.Red;
            textBox4.BackColor = Color.Yellow;
        }

        private void button1_Click(object sender, EventArgs e)
        {
            temizle();
        }
         

        private void button2_Click(object sender, EventArgs e)
        {
            renklendir();
        }
    }
}

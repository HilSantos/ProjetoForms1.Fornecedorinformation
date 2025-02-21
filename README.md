# ProjetoForms1.Fornecedorinformation
Criar as propriedades dos dados do fornecedor.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForms1
{
    public class Fornecedorinformation
    {
        //atalho propfull+tab tab
        private int codigo;

  public int Codigo
        {
            get { return codigo; }
            set { codigo = value; }
        }
        private string nome;

  public string Nome
        {
            get { return nome; }
            set { nome = value; }
        }
        private string cnpj;

  public string Cnpj
        {
            get { return cnpj; }
            set { cnpj = value; }
        }
        private string fone;

  public string Fone
        {
            get { return fone; }
            set { fone = value; }
        }
    }
}

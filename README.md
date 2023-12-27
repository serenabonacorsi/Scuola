# Scuola
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace scuolo
{
    internal class Insegnanti
    {
        public string Nome { get; set; }
        public string Cognome { get; set; }
        public DateTime dt { get; set; }
    }
}
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace scuolo
{
    internal class Studente
    {
        public string Nome { get; set; }
        public string Cognome { get; set; }
        public DateTime dt0 { get; set; }
    }
}
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace scuolo
{
    internal class Materia : Insegnanti
    {
        public string Nome { get; set; }
        public string Descrizione { get; set; }
    }
}
using scuolo;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace scuola
{
    internal class Voti
    {
        public DateTime Data { get; set; }
        public Materia materie { get; set; }
        public double Valore { get; set; }

    }
}

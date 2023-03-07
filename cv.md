Tatsiana Khizhniak
=
**Software engineer**
-----------  
**Contact information:**

**Phone:** +375 (44) 751-37-27  
**E-mail:** tanya86hizh@gmail.com  
**Telegram:** @tanyahizh  
**Githab:** [tanyahizh](https://github.com/tanyahizh)
******  

**About myself**  

I like to study. Also I am interested in psychology.
I have programming and teaching skills. I have a large family (3 children), which helps me to plan correctly and do everything in time. I enjoy working in a team, take the initiative, listen to advice and adequately respond to criticism. I attentively relate to detail, stress-resistant.
***
**Skills**
* C/C++/C#
* HTML/CCS/PHP(base)
* xBase(FoxPro)
* SQL
* Java(base)
* JavaScript(base)
* Visual Studio
* Microsoft SQL Server Management Studio
***
**Code example**  

The program was developed in .NET Framework(C#). This function **RefDataGrid(dgw, p)** updates the data in the form table using an SQL query.
```
private void RefDataGrid(DataGridView dgw, object p)
        {
            dgw.Rows.Clear();

            string querystring = $"select id, datak, snbolls, datan, kolday, ctxtDiagKlinZaklKod_1, dsctxtDiagKlinZaklKod, nstr, 
				prim, FIO, txtNumberIB, DATDATEBOUND, age, adressmzh, mrab, vidnp, vrvidbol, vrzakrbol, datreg 
				from bolnich_register where idp = '{p}'";

            SqlCommand command = new SqlCommand(querystring, db.getConnection());
            
            SqlDataReader reader = command.ExecuteReader();

            while (reader.Read())
            {
                ReadSingleRow(dgw, reader);
            }
            reader.Close();
        }
```
***
**Education/Courses**
* Francisk Skorina Gomel State University (faculty of mathematics and technologies of programming - mathematician-programmer, teacher of mathematics and computer science)
* Trained on platforms Netology, Geekbrain, Coursera, Learn.epam
***
**Experience**
* Software engineer in Company "Gomel Maltal and Normal Molders Plant"(2009-2012)
* Software engineer in "Republican scientific and practical center for radiation
medicine and human ecology"(2012-to the present day)  
***
**Languages**  

- Russian(native) 
- Belorusian(school education
)
- English (A2 - Epam testing)


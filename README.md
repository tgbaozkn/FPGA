# FPGA
## What is an FPGA? FPGA nedir 
### Field -Alan
### Programmable- Programlanabilir
### Gates-Kapılar(Mantık Kapıları-Boolean Fonksiyonları)
### Array (Dizi)
#### Çevirmek gerekirse Programlanabilir Mantık Kapıları Dizilerinden oluşan Alana sahip entegre(birleşik) devrelerdir. 
##### Programlabilir demek,istediğimiz fonksiyonu(boolean) istediğimizle değiştirebileceğimiz anlamına ,onu programlayabileceğimiz,editleyebileceğimiz ve istediğimizi kaldırabileceğimiz anlamına gelir. 
##### Boolean Fonksiyonları nedir derseniz Girişler(Inputs) ve Çıkışları (Outputs) "1" ya da "0" değeri yani  ya hep ya hiç ya da True -False değeri alan fonksiyonlardır örnek olarak AND,OR ,NAND(NOT AND) ,NOR(Not OR) vb. verilebilir. 
##### Sayısal devrelerin analizinde ve sayısal devrelerin programlanmasında , bu fonksiyonlar ve döndükleri kapılar kullanılır. Sayısal devre dediğimiz de birden fazla girişle bir çıkışı alan,transistörler,diyotlar vb elektronik elemanlardan oluşan giriş ve çıkışların sayısal olarak/boolean belirtildiği devrelerdir.Anahtarlama devreleri olarak dediğimiz sonucu kesin olan devreler sayısal devrelerdir.Anahtarlama en basit haliyle örnek verecek olursam butonlar diyebilirim Açık:1 , Kapalı :0 outputları bu şekildedir,buna göre de Açıkken bilgisayar açılır,kapalıyken kapanır. 
- Bu AND,OR vb dediğimiz mantık kapıları sayısal devrelerde transistörler,diyotlar,opamplar gibi elektronik elemanlarla yapılır. Görsellerde bu kapıları,transistörlerle yapılan kapıları görebilirsiniz. 
- Entegre devrelerde; sıradan entegre devrelerde kapıları istediğiniz gibi kaldırıp değiştiremezsiniz ve aynı anda her işi yaptıramazsınız.FPGA de ise mantık kapılarını kodlanabilen iki dili VHDL /Verilog sayesinde kodunuza göre transistörler birbirine ona göre bağlanır ,mantık kapılarını oluşturur,değiştirilebilirdir. FPGA ler de yapılan komutlar birbirine paralel olduğu için aynı anda bir çok işi yapabilir.Kendimizden benzetme yapacak olursak aynı anda görmek,koşmak,yemek yemek,konuşmak gibi her işi aynı anda yapabilir.

## FPGA'ler özetle 100lerce 1000lerce mantık(boolean) kapılarından oluşabilen ve bu kapıların istenilen zmaan istenilenle değiştirilebilen,programlanan ve programlanan kodların paralel olması sebebiyle aynı anda istenilen her işi yapan entegre devrelerdir.
# In English 
 ```
- FPGA: Field Programmable Gates Array is integrated circuits.
Programmable means that we can change functions(boolean) with what we want,we can programme, we can modify when we want, and we can delete.
Boolean functions are logic functions so they have many inputs and one output. The value of these inputs and output is "1" or "0". The logic of this function is all or nothing. For example,AND gate,OR gate,NAND Gate(Not AND),and NOR (Not OR) Gate, etc. 
This functions and this gates are used for digital circuit analysis,programming digital circuits. Digital circuits mean that you have inputs more than one and you have one output,both of they are boolean.These circuits occur with transistors,diodes and electronic devices. 
AND ,OR,NAND,NOR Gates consist of transistor,diodes,opamps in digital circuits. In images,you can see these gates. 
In the common integrated circuits,you cant change gates what you want and you can't have it made every work with they.But in FPGAs,you can do everything what you want because works of FPGA parallel to each other and you use VHDL or Verilog when coding FPGA so you can shape transistors what you want.


 ```

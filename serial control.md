#### string to bytes
ByVal command As String  
Dim bytes() As Byte = System.Text.Encoding.ASCII.GetBytes(command & vbCrLf)  

#### bytes to string
Dim data As [Byte]()  
Dim s As New String(System.Text.ASCIIEncoding.ASCII.GetChars(data))  



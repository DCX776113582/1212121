# 1212121
111111
string  opertaor + (string & tt)
{
  char * cc = new char[len+tt.len+1];
  strcpy(cc,rep);
  strcat(cc,tt.rep);
  string gg(cc);
  delete cc;
  return gg;
}
string & opertaor+=(string& tt )
{
  len +=tt.len;
  char * cc = rep;
  rep = new char [len+1];
  strcpy(rep,cc);
  delete cc;
  strcat(rep,tt.rep);
  return *this;
}


hjfgjhgjkhgjkh
kjhgkjhgkjhkjhkj


xxxxxxxx

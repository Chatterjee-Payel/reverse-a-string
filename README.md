# reverse-a-string
char* reverse(char *S, int len)
{
    //code here
   stack<char>ch;
   for(int i=0;i<len;i++){
        ch.push(S[i]);
        
   }
   int j=0;
   while(!ch.empty())
   {
       S[j++]=ch.top();
       ch.pop();
       
   }
   return S;
   
}

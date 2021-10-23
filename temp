#include<process.h>
#include<conio.h>
#include<stdio.h>
int main(int argc,char *argv[])
{
FILE *fin,*fout; char c;

if(argc!=3)
{
printf("\n insufficient argument "); exit(1);
}
fin=fopen(argv[1],"r");
fout=fopen(argv[2],"w");

while(!feof(fin))
{
c=fgetc(fin); fputc(c,fout);
}

fclose(fin); fclose(fout); return 0;

}

# Opposing_homozygositys_offspring_parents_based_on_pedigree

Parentage analysis (calculating the opposing homozygosity) between individuals and their parents based on a pedigree

OHfinder_ped is a FORTRAN code that can be downloaded along with a toy example. The full example can be found in the parameter file.


8                           !Number of ind           
10                         ! Number of SNP       
ped.txt                    ! Name of ped file         
eno.txt                    ! Name of geno file      
out.txt                    ! Name of output file 

-----------------------------------------------             
Ped file starts from 1 to n; where n is the total  number of animals 
 The output file contains 9 columns:          
 1. Individual ID                               
 2. Parent ID                                   
 3. Total number of SNPs                        
 4. Number of informative SNPs                  
 5. Number of SNPs with mismatch                
 6. Number missing SNPs for individual          
 7. Number missing SNPs for parent              
 8. Number missing SNPs in both                 
 9. % of SNPs with mismatch                     

There is also some available parentage analysis packages such as Cervus. I think the free version is available only for Windows and can handle only a small number of individuals. 

http://www.fieldgenetics.com/pages/aboutCervus_Overview.jsp

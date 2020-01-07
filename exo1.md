mkdir cli_tmp
touch cli_tmp/je_suis_dans_tmp.txt
cd cli_tmp
touch in_cli_tmp.txt
mkdir in_cli_tmp
rm je_suis_dans_tmp.txt
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir.txt
mv bachir.txt ../ami
cd ..
cp -r ami parent
cd ami
rm bachir.txt
pwd
cd ..
rm -r cli_tmp
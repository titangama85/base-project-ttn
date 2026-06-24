for i in {1..100}; do echo "Update $i" >> progress.txt; git add progress.txt; git commit -m "chore: base build update series-$i"; done

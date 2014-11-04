Very deeply nested files.

Generated with:

    for i in {0..2000}; do echo $i; mkdir d; cd d;                     done; touch a; git add a
    for i in {0..2000}; do echo $i; mkdir e; cd e; touch a; git add a; done;

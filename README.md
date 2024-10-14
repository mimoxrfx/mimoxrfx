if(mode == "Visa"):
    types = input("Card Or Prepaid Code? ")
    if(types == "Prepaid Code"):
        gentype = '0123456789'
        for x in range(number):
            generate1 = random.choice(gentype)
            generate2 = random.choice(gentype)
            generate3 = random.choice(gentype)
            generate4 = random.choice(gentype)
            generate5 = random.choice(gentype)
            generate6 = random.choice(gentype)
            generate7 = random.choice(gentype)
            generate8 = random.choice(gentype)
            generate9 = random.choice(gentype)
            generate10 = random.choice(gentype)
            generate11 = random.choice(gentype)
            generate12 = random.choice(gentype)
            generate13 = random.choice(gentype)
            generate14 = random.choice(gentype)
            generate15 = random.choice(gentype)
            generate16 = random.choice(gentype)
            newline = "\n"
            space = " "
            gen1 = random.choice(gentype)
            gen2 = random.choice(gentype)
            gen3 = random.choice(gentype)
            gen4 = random.choice(gentype)
            gen5 = random.choice(gentype)
            gen6 = random.choice(gentype)
        
        
            with open(file, 'a') as out:
                out.write(generate1+generate2+generate3+generate4+generate5+generate6+generate7+generate8+generate9+generate10+generate11+generate12+generate13+generate14+generate15+generate16+newline)
            with open(file2, 'a') as out2:
                out2.write(gen1+gen2+gen3+gen4+gen5+gen6+newline)

# gc_content
def gc_content(seq):
    """GC content in a DNA/RNA sequence"""
    return round((seq.count('C')+ seq.count('G')) / len(seq) * 100)

DNA_GC = "ACGCTCGATCGTAGCGAGGAGCGATGACGATCGAGAGATAGAGCGCCCGTAGCGATCGAACGCT"

print(gc_content(DNA_GC))

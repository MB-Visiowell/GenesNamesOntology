"""
This 2-parts project aims at automatically identifying gene names from a Zotero library and creating a list of harmonised gene names from that 

...
1x - Output CSV
--> Manual part during which you have to select if all identified 
2- Scrapping on Wikipedia 
2a - Input CSV
2b -
...
2x - Export updated CSV with all 

"""
import numpy as np
# import beautifulsoup ?

#########

def Zotero_opening():
    """
    Choose the proper Zotero library and screen each paper to find gene names

    Parameters
    ----------
    input : name of Zotero library & local access on your computer

    Returns
    -------
    result : list of gene names in a CSV that can easily be modified 

    """

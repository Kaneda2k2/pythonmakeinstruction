import argparse
 
parser = argparse.ArgumentParser()
parser.add_argument("-v", "--verbose","-d","--daniel",help="Mostrar información de depuración", action="store_true")
args = parser.parse_args()
 
# Aquí procesamos lo que se tiene que hacer con cada argumento
if args.verbose:
    print("depuración activada!!!")
    if args.verbose:
        print("daniel ha creado este programa")

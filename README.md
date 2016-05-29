# Main
Comporte les fichiers src sur projet
#TODO
faire la comm entre les couleurs choisies et la previsualisation

#fonction HEXA TO RGB :
public static Color hex2Rgb(String colorStr) {
    return new Color(
            Integer.valueOf( colorStr.substring( 1, 3 ), 16 ),
            Integer.valueOf( colorStr.substring( 3, 5 ), 16 ),
            Integer.valueOf( colorStr.substring( 5, 7 ), 16 ) );
}

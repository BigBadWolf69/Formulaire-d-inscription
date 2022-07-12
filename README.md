<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form>
        <fieldset>
            <legend>Formulaire d'inscription</legend>
                <table>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <label>Nom </label>
                </td>
                <td>
                    <input type="text" name="Nom" id="Nom"placeholder="saisir votre nom" />
                </td>
            </tr>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <label>Prénom </label>
                </td>
                <td>
                    <input type="text" name="Prénom" id="Prénom"placeholder="saisir votre prénom" />
                </td>
            </tr>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <label>Email </label>
                </td>
                <td>
                    <input type="text" name="Email" id="Email"placeholder="saisir votre Email" />
                </td>
            </tr>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <label for="Sexe">Sexe</label>
                </td>
                <td>
                    <input type="radio" id="Sexe" name="Sexe" value="Masculin"/>Masculin
                    <input type="radio" id="Sexe" name="Sexe" value="Féminin"/>Féminin
                </td>
            </tr> 
        <tr><td><p></p></td></tr>   
            <tr>
                <td>
                    <label for="avatar">Photo</label>
                </td>
                <td>
                    <input type="file" id="avatar" name="avatar" accept="image/png, image/jpeg">
                </td>
            </tr>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <label for="pays">Pays</label>
                </td>
                <td>
                    <select name="pays" id="pays">
                        <option value="france">France</option>
                        <option value="espagne">Espagne</option>
                        <option value="italie">Italie</option>
                        <option value="royaume-uni">Royaume-Uni</option>
                        <option value="chine">Chine</option>
                        <option value="japon">Japon</option>
                    </select>
                </td>
            </tr>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <label for="Langages">Les langages préférés</label>
                </td>
                <td>
                    <select multiple name="Langages" id="Langages">
                        <option value="CSS">CSS</option>
                        <option value="HTML">HTML</option>
                        <option value="JAVAscript">JAVAscript</option>
                        <option value="PHP">PHP</option>
                        <option value="SQL">SQL</option>
                    </select>
                    (Pour faire plusieurs choix maintenir la touche CTRL enfoncée)
                </td>
            </tr>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <label>Domaine d'activités</label>
                </td>
                <td>
                    <input type="checkbox" name="Informatique" id="Informatique" /> <label for="Informatique">Informatique</label>
                    <input type="checkbox" name="Gestion" id="Gestion" /> <label for="Gestion">Gestion</label>
                    <input type="checkbox" name="Pédagogie" id="Pédagogie" /> <label for="Pédagogie">Pédagogie</label>
                </td>
            </tr>
        <tr><td><p></p></td></tr>
            <tr>
                <td>
                    <input type="submit" value="Envoyer">
                    <input type="submit" value="Annuler">
                </td>
            </tr>
                </table>
        </fieldset>
    </form>
</body>
</html>

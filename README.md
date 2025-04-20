# Etudiant
Etudiant of homework

package dz.univeloued.tps.classes;

public class Etudiant extends Personne {
    private String mat;
    private String domain;

    public Etudiant(int id, String nom, String prenom, String mat, String domain) {
        super(id, nom, prenom);
        this.mat = mat;
        this.domain = domain;
    }

    @Override
    public String toString() {
        return super.toString() + " mon MAT est: " + mat;
    }
}

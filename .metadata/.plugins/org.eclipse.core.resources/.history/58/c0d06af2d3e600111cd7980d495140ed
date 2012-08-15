package sessionbeans;

import javax.ejb.Remote;
import javax.ejb.Stateless;

@Stateless
@Remote(LancadorDeDadoBean.class)
public class LancadorDeDadoBean implements LancadorDeDado {

	@Override
	public double lanca(){
		return this.gerador.nextInt(5) +1;	
	}
}

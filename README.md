## Simulaciones de red

Este repositorio contiene dos simulaciones de red de los ganglios basales (incluyendo al STN y al GPe).

 - `terub/terub-network.ipynb`. Usa los modelos de Terman y Rubin para el STN y el GPE disponibles en NESTML. Se aplican el resto de parámetros de Shouno.
 - `otsuka/otsuka-network.ipynb`. Usa el modelo de Otsuka para el STN implementado a través de NESTML. Se aplican el resto de parámetros de Shouno.

## Modelos de neurona 

### Pruebas sobre los modelos de Terman y Rubin para el STN y el GPe

- `terub-single-spike.nestml`. Pruebas unicelulares sobre los modelos de Terman y Rubin.

### Implementación del modelo de Otsuka para el STN

- `otsuka_stn.nestml`. Implementación a través de NESTML del modelo descrito en Otsuka.
- `otsuka-single-spike.nestml`. Pruebas unicelulares sobre el modelo de Otsuka.


## Referencias

- Terman, D., Rubin, J. E., Yew, A. C., & Wilson, C. J. (2002). Activity patterns in a model for the subthalamopallidal network of the basal ganglia. Journal of Neuroscience, 22(7), 2963-2976.
- Otsuka, T., Abe, T., Tsukagawa, T., & Song, W. J. (2004). Conductance-based model of the voltage-dependent generation of a plateau potential in subthalamic neurons. Journal of neurophysiology, 92(1), 255-264.
- Shouno, O., Tachibana, Y., Nambu, A., & Doya, K. (2017). Computational model of recurrent subthalamo-pallidal circuit for generation of parkinsonian oscillations. Frontiers in Neuroanatomy, 11, 21.

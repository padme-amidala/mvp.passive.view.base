# ~MVPPVI~
This sample solution implements the basic concept of the model view presenter pattern with passive views. The passive views work great with complex view data and rely on pure unit tests. Please feel free to suggest any improvements.

The [Mvp.Passive.View.Base.Model](https://github.com/HofmeisterAn/mvp.passive.view.base/tree/master/Mvp.Passive.View.Base.Model) is an abstract implementation of the model. This provides a low coupling and an easy implementation of other data sources. The project contains the model objects and all necessary interfaces to access the information. These interfaces are implemented by the [Mvp.Passive.View.Base.Database](https://github.com/HofmeisterAn/mvp.passive.view.base/tree/master/Mvp.Passive.View.Base.Database) project which applies the specific data access. The main project [Mvp.Passive.View.Base.Main](https://github.com/HofmeisterAn/mvp.passive.view.base/tree/master/Mvp.Passive.View.Base.Main) put everything together. It contains the presenter and also the view.

## Obsolete

Use [MVPPVI2](https://github.com/padme-amidala/mvp.passive.view.base2) instead.

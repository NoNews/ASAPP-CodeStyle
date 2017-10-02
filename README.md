### View elements


  - TextView :  `tv_name`
  - ImageView: `iv_name`
  - Button: `btn_name`
  - CircleImageView: `civ_name`
  - CardView: `cv_name`
  - LinearLayout, FrameLayout, RelativeLayout, AbsoluteLayout, CoordinatorLayout: `lt_name` 

### Dipendency Injection

#### Inject presenter
`@InjectPresenter lateinit var tabContactsSearchPresenter: TabContactsSearchPresenter`

#### Provide presenter
`@ProvidePresenter fun provideTabContactsPresenter(): TabContactsPresenter = Injector.logicComponent!!.tabContactsPresenter`

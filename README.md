### View elements


  - TextView :  `tv_name`
  - ImageView: `iv_name`
  - Button: `btn_name`
  - CircleImageView: `civ_name`
  - CardView: `cv_name`
  - LinearLayout, FrameLayout, RelativeLayout, AbsoluteLayout, CoordinatorLayout: `lt_name` 

### Inject and provide presenter

   `@InjectPresenter lateinit var tabContactsSearchPresenter: TabContactsSearchPresenter`
   `@ProvidePresenter fun provideTabContactsPresenter(): TabContactsPresenter = Injector.logicComponent!!.tabContactsPresenter`

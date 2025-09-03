# Dacchuking

r1.js
+14
-18
Lines changed: 14 additions & 18 deletions
Original file line number	Diff line number	Diff line change
@@ -1,28 +1,24 @@
class Header extends React.Component {
  render() {
    // Classes to add to the <input /> element
    let searchInputClasses = ["searchInput"]:
    // Update the class array if the state is visible
    if (this.state.searchVisible) {
      searchInputClasses.push("active");
    }
    return (
      <div className="header">
        <div className="fa fa-more"></div
      <div
        className="header"
        style={{
          backgroundColor: "rgba(251, 202, 43, 1)"
        }}
      >
        <div className="menuIcon">
          <div className="dashTop"></div>
          <div className="dashBottom"></div>
          <div className="circle"></div>
        </div>

        <span className="title">-
          {this.props.title}
        </span>
        <span className="title">{this.props.title}</span>

        <input
          type="text"
          className={searchInputClasses.join(' ')}
          placeholder="Search ..." />
        <input type="text" className="searchInput" placeholder="Search ..." />

        <div className="fa fa-search searchIcon"></div>
      </div>

}
‎day-01/package.json
-53
Lines changed: 0 additions & 53 deletions
This file was deleted.
